# Data Analysis using SQL and Python
I embarked on this project to delve into the world of data analysis using SQL and showcase my skills in exploring and extracting valuable insights from complex datasets. The European Soccer Database, with its rich and comprehensive collection of soccer-related data, provided the perfect opportunity to apply SQL, Python, and libraries such as Pandas, Matplotlib, and Seaborn. This project allowed me to gain practical experience in data manipulation, aggregation, and analysis, leveraging both SQL and Python's powerful tools for a thorough exploration of the dataset.


## Project Overview
The European Soccer Database is an extensive resource designed for soccer enthusiasts, analysts, and machine learning practitioners. Featuring a vast collection of over 25,000 matches, 10,000 players, and detailed attributes derived from the FIFA video game series, this dataset provides a wealth of information for in-depth analysis and exploration.

## Comprehensive Overview of the European Soccer Database
* ***Matches:*** Includes data from over 25,000 recorded matches between 2008 and 2016 across 11 European countries.
* ***Players:*** Contains information on more than 10,000 players, featuring attributes from the FIFA video game series.
* ***Leagues:*** Provides details about the top championship leagues in 11 European countries.
* ***Team Lineups:*** Offers detailed squad formations with X and Y coordinates.
* ***Betting Odds:*** Features betting odds data from up to 10 different providers.
* ***Match Events:*** Covers comprehensive match events such as goal types, possession, corners, fouls, and more.
<br>
<br>
![wget]([https://github.com/pratikphirke07/PWC_Dashboards/blob/main/Certificate.png](https://raw.githubusercontent.com/pratikphirke07/DataAnalysis_SQL_Python/main/Database_Schema.jpg)
<br>
<br>
## Overview of each SQL clause used in the project:

* ***SELECT:*** The SELECT clause determines which columns or expressions will be included in the result set of the query. It's the primary way to specify what data you want to retrieve from the database.
* ***FROM:*** The FROM clause specifies the tables from which to retrieve the data. It forms the foundation of the query, defining the data sources and their relationships.
* ***JOIN:*** The JOIN clause is used to combine rows from two or more tables based on a related column between them. It allows you to merge data from different tables, enabling more complex and insightful queries.
* ***WHERE:*** The WHERE clause is used to filter records, retaining only those that meet specific conditions. It allows you to narrow down the dataset based on criteria such as values in certain columns or comparisons between columns.
* ***GROUP BY:*** The GROUP BY clause is used to group rows that have the same values in specified columns. It's typically used with aggregate functions like SUM, AVG, COUNT, etc., to perform calculations on each group rather than on the entire dataset.
* ***HAVING:*** The HAVING clause is used in conjunction with the GROUP BY clause to filter group rows based on specified conditions. It's similar to the WHERE clause but operates on grouped rows rather than individual rows.
* ***ORDER BY:*** The ORDER BY clause is used to sort the result set by one or more columns in ascending or descending order. It allows you to control the presentation of data, making it easier to read and analyze.
* ***LIMIT:*** The LIMIT clause is used to constrain the number of rows returned by a query. It's useful for situations where you only need to see a subset of the results, such as when working with large datasets or for pagination purposes.
* ***Common Table Expressions (CTE):*** CTEs are temporary result sets that can be referenced within a SELECT, INSERT, UPDATE, or DELETE statement. They allow you to break down complex queries into more manageable parts and improve readability.
* ***Aggregate Functions (e.g., AVG, SUM, COUNT):*** Aggregate functions perform calculations on a set of values and return a single value.
  * AVG: Calculates the average of a set of values.
  * SUM: Adds up all the values in a set.
  * COUNT: Counts the number of rows in a set.
These functions are often used with the GROUP BY clause to perform calculations on groups of rows rather than the entire dataset.
* ***DISTINCT:*** The DISTINCT keyword is used to eliminate duplicate rows from the result set. It ensures that only unique rows are returned, which can be useful when you want to see unique values in a column or combination of columns.
* ***ROUND Function:*** The ROUND function is used to round a numeric value to a specified number of decimal places. It can also be used to round to the nearest integer if no decimal places are specified.
* ***COALESCE Function:*** The COALESCE function is used to return the first non-null value in a list of expressions. It's useful for handling null values and providing a default value when a column may be null.

## Import libraries used for Data Manipulation and Visualization in Python:
* ***pyodbc:*** Provides access to ODBC databases, allowing you to connect to and interact with various database management systems.
* ***pandas:*** Offers data structures and tools for data manipulation and analysis. It's particularly useful for working with tabular data.
* ***sqlite3:*** Provides a lightweight disk-based database that doesn't require a separate server process. It's useful for managing small to medium-sized databases.
* ***matplotlib.pyplot:*** A plotting library for creating static, animated, and interactive visualizations in Python. It's commonly used for basic plotting needs.
* ***seaborn:*** Built on top of matplotlib, seaborn provides a high-level interface for drawing attractive and informative statistical graphics. It's particularly useful for enhancing the aesthetics of your plots.

## Dataset source: https://www.kaggle.com/datasets/hugomathien/soccer
