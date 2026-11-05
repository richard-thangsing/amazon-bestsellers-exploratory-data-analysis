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
- 'MAXIFS' and 'MINIFS'
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

### 4. Top 5 Books by Reviews

The books were sorted by review count to identify the five titles with the highest number of reviews.

| Rank | Book Title | Reviews | Author | Genre |
|------|------------|---------|--------|-------|
| 1 | Where the Crawdads Sing | 87841 | Delia Owens | Fiction |
| 2 | The Girl on the Train | 79446 | Paula Hawkins | Fiction |
| 3 | Becoming | 61133 | Michelle Obama | Non Fiction |
| 4 | Gone Girl | 57271 | Gillian Flynn | Fiction |
| 5 | The Fault in Our Stars | 50482 | John Green | Fiction |

> Since the analysis is done on an older Excel 2019 same title appears in multiple years, to handle that we used a classic Excel array formula to extract a unique, ranked list of items based on their total reviews, while systematically ignoring items that have already been listed to successfully break ties.

> On Microsoft 365 or Excel 2021+, a single, dynamic formula using INDEX + SORT + FILTER placed in the top cell can automatically handles ties and sorts the data instantly.

### 5. PivotTable Analysis

PivotTables were used to summarize and compare the data from different perspectives. These include:
- Number of books by genre
- Average rating by genre
- Total reviews by author
- Average price by genre
- Number of books by year
- Ratings or reviews over time
- Top authors based on review count

### 6. Dashboard and Interactivity

PivotCharts were added to visualize the results of the analysis. Slicers allow users to filter the dashboard interactively. This provides a more user-friendly way to explore the dataset without editing formulas or manually filtering the raw data.

---

## Key Findings

1. **Genre distribution:**

   Non-fiction leads both total title volume (310 titles vs. 240 titles) and overall revenue ($4,601 vs. $2,604) across the 2009 - 2019 period. This provides us an insight into readers' psychology as the majority of the readers in our study prioritize utilitarian value over pure entertainment. 
3. **Average rating:**
4. **Review activity:**
5. **Top-performing book:**
6. **Author performance:**
7. **Price pattern:**
8. **Yearly trend:**
---

## Dashboard Preview


