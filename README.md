# Automating Basic Dataset Cleaning and Quick Guide to Data Wrangling
This repository provides a function that automates basic dataset cleaning. The Jupyter Notebook also guides us in contextual data cleaning. This is my quick step-by-step guide for data wrangling.

# Problem
Data cleaning is a necessary part of data analysis. We need to ensure that our dataset is wrangled properly because the accuracy of our analysis and visualization depends on the accuracy of the data themselves. However, some processes of data wrangling are repetitive. Can we streamline our data preparation? 

# Plan
With the help of Pandas, I have to code a Python function that answers this problem. The basic cleaning steps that are repetitive and apply to any dataset are (1) removing empty rows, (2) removing whitespace, and (3) removing duplicate rows. Once we call the function, it should automatically return a cleaned dataframe. Unfortunately, some formatting cannot be automated (i.e. renaming columns to certain names, transforming data types of some columns to certain types, etc.). Thus, I want to create a user-friendly Jupyter Notebook that not only presents our automation function for basic cleaning but also guides us to other contextual wrangling processes (with sample codes). 

# Screenshot of the dirty dataset
![ToClean](https://github.com/marvin-rubia/Automate-Basic-Dataset-Cleaning-and-Guide-to-Data-Wrangling-in-Python/assets/140475770/936268e1-d6a3-4367-8792-35b17b0c1060)

# Screenshot of the cleaned dataset
![Cleaned](https://github.com/marvin-rubia/Automate-Basic-Dataset-Cleaning-and-Guide-to-Data-Wrangling-in-Python/assets/140475770/9ccb0235-b2ea-4ee2-a8eb-0008aba3d229)

# How to see my cleaning function and guide to data wrangling? 
Check the uploaded Jupyter Notebook for the codes. It guides anyone with an example. If you are going to download the Notebook, you might want to download the __dirty__ .csv file. You can also follow along with your own dataset that you need to clean. 

