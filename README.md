<!-- Add banner here -->

![undraw_predictive_analytics_kf9n](https://user-images.githubusercontent.com/83410546/136421085-2bb85226-f3f6-4ab5-84a8-965edec161b0.png)

# Sales-Prediction-Analysis

<!-- Add buttons here -->
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/ridhed/Sales-Prediction-Analysis?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/ridhed/Sales-Prediction-Analysis)
![GitHub issues](https://img.shields.io/github/issues-raw/ridhed/Sales-Prediction-Analysis)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ridhed/Sales-Prediction-Analysis)
![GitHub](https://img.shields.io/github/license/ridhed/Sales-Prediction-Analysis)

<!-- Described the project in brief -->
This is the Sales-Prediction-Analysis on SuperStore sales dataset given to us by mentor Balwant Gorad of Tech saksham Program.
The Notebook described in the section will query for the business growth from sales dataset to retrieve the desired data based on few constraints.


# Table of contents

- [Project Title](#project-title)
- [The basic Libraries used in Sales Analysis Project](#the-basic-libraries-used-in-sales-analysis-project)
- [How I Did The Superstore Sales Dataset Analysis](#how-i-did-the-Superstore-sales-dataset-analysis)

# The basic Libraries used in Sales Analysis Project 
* Data Collection – Conducting opinion Surveys, scraping the internet, etc.
* Data Handling – Viewing data as a table, performing cleaning activities like checking for spellings, removal of blanks and wrong cases, removal of invalid values from data, etc.
* Data Visualization – plotting appealing graphs, so anyone who looks at the data can know what story the data tells us.
 1) Pandas – short for “Panel Data” (A panel is a 3D container of data) – is a library in python which contains in-built functions to clean, transform, manipulate, visualize                  and analyze data.
 
 2) NumPy – Numerical python – forms the basics of what pandas is all about. While NumPy deals with “Arrays” and “Matrices”, Pandas deals with “Series” & “Data Frames”.

 3) Matplotlib- It is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding                     plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK.

 4) Seaborn- Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation              to produce informative plots. 
 
[(Back to top)](#table-of-contents)

# How I Did The Superstore Sales Dataset Analysis

Functions Used For Analysis

* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.
* isna() - function is used to detect missing values. It return a boolean same-sized object indicating if the values are NA
* groupby() - dataframe.groupby() function is used to split the data into groups based on some criteria. pandas objects can be split on any of their axes. 
              The abstract definition of grouping is to provide a mapping of labels to group names.  

Questions Answered/Analysed From The Dataset

* Q.1) What is overall sales trend?
* Q.2)Which are top 10 products by sales?
* Q.3)Which are the most selling products (quantity)?
* Q.4)Which is the most preferred shipping method ?
* Q.5)Which are the most profitable categories and sub categories ?
* Q.6)Which are the least profitable categories and sub categories ?
* Q.7)Which are bottom 10 prodcts by sales ?
* Q.8)Which are the least selling products (qauntity)?
* Q.9)In which year did we got more orders ?
* Q.10)Find from which we got more order from ?
       
[(Back to top)](#table-of-contents)


[GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0)
