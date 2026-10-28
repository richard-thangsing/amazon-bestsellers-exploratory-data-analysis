# Amazon Bestsellers Exploratory Data Analysis (EDA)

## Project Overview
This project presents an exploratory data analysis of an Amazon bestsellers dataset using Microsoft Excel. The goal is to analyze book performance, identify patterns across genres and authors, 
and create an interactive dashboard that allows users to explore that data. Also use some visualizations using charts to help the users identify the trends and patterns at a glance. 

The analysis includes summary statistics, genre-level comparisons, author and genre lookups, books recommendation based on reviews, author power ranking, PivotTables, Pivot Charts, slicer, and more.

>**Note:** This is an independent data analysis project created for educational and portfolio purposes. It is not affiliated with or endorsed by Amazon.

---
## Project Objectives
The main objectives of this project are to:
- Summarize the overall size and composition of the dataset
- Calculate key book-performance metrics
- Compare Fiction and Non Fiction books
- Identify books with the highest number of reviews
- Explore author and genre information using lookup formulas
- Build PivotTables for grouped analysis
- Create interactive Pivot Charts and slicers
- Present the findings in a simple Excel dashboard

---
## Dataset
The dataset contains information about bestselling books, as specified below:

'Name | Author | User Rating | Reviews | Price | Year | Genre'

---

## Dataset Summary
- **Total books:** 550
- **Unique book titles:** 350
- **Unique authors:** 258
- **Average user rating:** 4.62
- **Median rating:** 4.7
- **Total reviews:** 6574305
- **Average price:** $13.1
- **Years covered:** 2009 - 2019

---
## Tools and Excel Features Used
- Microsoft Excel
- Excel Tables
- Sorting and Filtering
- 'AVERAGE' and 'AVERAGEIF'
- 'COUNT' and 'COUNTA'
- 'COUNTIF' and 'COUNTIFS'
- 'SUMIF' and 'SUMIFS'
- 'UNIQUE' or 'SUMPRODUCT'
- 'XLOOKUP' or 'VLOOKUP'
- 'INDEX' and 'MATCH'
- LARGE() function
- IFERROR() to catch all Excel error types: #N/A, #VALUE!, #REF!, #DIV/0!, #NUM!, #NAME?, and #NULL!.
- PivotTables
- PivotCharts
- Slicers
- Conditional formatting
- Dashboard formatting and layout
---
## Analysis Performed

### 1. Overall Summary Metrics
A summary section was created to provide a quick overview of the dataset. It includes metrics such as:
- Total number of books
- Number of unique titles
- Number of unique authors
- Average user rating
- Total number of reviews
- Average price

These metrics provide a high-level understanding of the dataset before moving into more detailed analysis.

### 2. Genre Breakdown

The books were grouped by genre to compare Fiction and Non Fiction titles.

The genre analysis includes:
- Number of books by genre
- Average rating by genre
- Total reviews by genre
- Average price by genre
- Genre distribution across the dataset

### 3. Author and Genre Lookup

An interactive lookup section was created to retrieve information for a selected book or author.

Depending on the lookup value entered, the workbook can return details such as:
- Author name
- Book title
- Genre
- User rating
- Number of reviews
- Price
- Publication year
- Number of books by the author
- Average rating
- Total reviews
- Average price of all the books by the author
- Average value score
- Highest rating
- Lowest rating

This section demonstrates the use of Excel lookup functions for retrieving information from a structured dataset.
