# Automating Basic Data Wrangling with the `clean_dataframe()` Function
I created a Python function—called `clean_dataframe()`—that automates the basic data wrangling of a given dataframe. The Jupyter Notebook provides simple documentation for the said function and an example of using it. Copy the code for my function if you want to use it to clean your dataframe. 

## Problem
Data cleaning is a necessary part of data analysis. We need to ensure that our dataset is wrangled properly because the accuracy of our analysis and visualization depends on the accuracy of the data themselves. However, some processes of data wrangling are repetitive. Can we streamline our data preparation? 

## Plan
With the help of Pandas, I have to code a Python function that answers this problem. In this way, I can process a given dataset in Python, create its dataframe, and pass it to the `clean_dataframe()` function. From here, I can either continue analyzing it in Python or save the cleaned dataframe into a .csv or .xlsx file. The cleaned dataset can then be loaded into Excel, Power BI, or Tableau to make an analysis and a dashboard.

## Screenshot of the dirty dataset
![ToClean](https://github.com/marvin-rubia/Automate-Basic-Dataset-Cleaning-and-Guide-to-Data-Wrangling-in-Python/assets/140475770/936268e1-d6a3-4367-8792-35b17b0c1060)

## Screenshot of the cleaned dataset
To clean our dataframe (of the dirty .csv dataset), we call the function with only this code `clean_dataframe(df, to_integer=['Equipment Count'])`. The resulting .csv file (after saving the cleaned dataframe) is shown below. 

![Cleaned](https://github.com/marvin-rubia/Automate-Basic-Dataset-Cleaning-and-Guide-to-Data-Wrangling-in-Python/assets/140475770/9ccb0235-b2ea-4ee2-a8eb-0008aba3d229)

## Note
The `clean_dataframe()` function does __not__ aim to cover _every_ possible data-wrangling process specific to your dataset. You still have to check the resulting dataframe and do more data wrangling if needed. The goal of the function is to reduce the time we spend coding repetitive data cleaning steps in our datasets.

Use my function if you want to automatically:
- remove empty rows,
- remove duplicate rows,
- remove trailing and leading whitespaces,
- transform double spaces into single spaces,
- (optional) change the types of specified columns into `int`, `float`, `str`, `bool`, or `datetime`
- (optional) replace the missing values of specified columns by the mean of the corresponding columns, and
- (optional) replace the missing values of specified columns by the mode of the corresponding columns.
