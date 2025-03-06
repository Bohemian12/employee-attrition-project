# Employee Attrition Analysis 

A exploratory data analysis on [IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data) on Kaggle to showcase my data analytics skills.


This Project is divided into 6 phases of data analysis which are-
1. Ask
2. Prepare
3. Process
4. Analyse
5. share
6. Act

# ASK

In this phase we need to just ask questions to get to know the scope and how to do and what questions to answer.

**Q1.** What are the top 5 common factors which effect the attrition rate of employees?  
**Q2.** What are the trends based on department?  
**Q3.** How salary affects the attrition of employees?
**Q4.** Which age group left the company most?  
**Q5.** Relation b/w employees who overtime and employees who left the company?  

These questions needed to be answered using this data by doing this it helps streamline the process of data analysis.

# PREPARE

In Prepare we need to found how we will collect the data will it be first hand or second hand data and many other things,
as per my project i have collected my data from kaggle a platform where you can find open source datasets to work with although this isn't the original company data its a made up data of company hr analytics.
now we know the data and where it comes from we can procced to process it.
This dataset have 1470 employees data in it.

# PROCESS

In this phase i will check the integrity of data and clean it accordingly using different tools and methods.
first i will check all the data constraints so that we don't miss anything i will do as followings:
* Datatype - checking all the columns data type 
* Data range - checking the columns should no go above a certian range
* Mandatory - some things can't be null in the data
* Unique - can't have duplicates
* regx patterns - some standarized patterns in data
* Cross-field validation - Certain conditions for multiple fields must be satisfied
* Accuracy -  match to the original survey 
* Completeness - this data is complete
* Consistency - all components are consistent
* Trim - Trimed all the data to make sure its clean using power query

## Recording Changes
most of columns were not correct datatype i used power query's detect datatype to quickly correct all the
columns's datatype.
There was a mistake in EmployeeCount column there is 'h' written in it all others are 1 because each row has only
data of 1 employee so i will change this inconsistent data to 1.


# ANALYSE
After cleaning the data we move on to next step which is analysis where we start with exploring the data first then moving deeper and finding the answer to the questions that we asked in the first phase. So, lets start with Exploring it In excel i used discriptive summary in **Data Analysis** tool in data tab on first age column and then monthly salary column, then using **COUNTIF** on **Attrition** column found out that 237 employees left the company and 1233 employess are currently in the company. After getting the hang of the data i imported the data table to PowerBI 

# SHARE 
# ACT



