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

**Q1.** What are the top common factors which effect the attrition rate of employees?  
**Q2.** What are the trends based on department?  
**Q3.** How salary affects the attrition of employees?
**Q4.** Which age group left the company most?  
**Q5.** what percent of employee who left were doing overtime?  

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

### Recording Changes
most of columns were not correct datatype i used power query's detect datatype to quickly correct all the
columns's datatype.
There was a mistake in EmployeeCount column there is 'h' written in it all others are 1 because each row has only
data of 1 employee so i will change this inconsistent data to 1.


# ANALYSE
After cleaning the data we move on to next step which is analysis where we start with exploring the data first 
then moving deeper and finding the answer to the questions that we asked in the first phase. So, lets start with
Exploring it In excel i used discriptive summary in **Data Analysis** tool in data tab on first age column and 
then monthly salary column, then using **COUNTIF** on **Attrition** column found out that 237 employees left the
company and 1233 employess are currently in the company. After getting the hang of the data i imported the data 
table to PowerBI and opened the data in power query to add new column **EmployeeStatus** by duplication of
Attrition column then replacing Yes with Non-Working and No with Working to make it more clear in the
visualizations we will make. Then made a stacked column chart using average of monthly income with newly made
employee status column to show the contrast that people who left or non-working used to get less income when 
compared to working employees this can be because the people who left were young and has less income but when i 
compared average age then diffrence was of approx 4 years which can be the factor for monthly income this dosen't 
give us clearity. Then segmenting the monthly income column into three parts low, medium & high income employees after that created a DAX measure **AttritionRate** which will show the attrition rate after visualizing both the segmentation of income and attrition rate we found out that attrition rate of low income employee are way higher that the other two which tells us that the salary is affecting the low income employees and they are going to find high income jobs.
After that made it into a bar chart which answered our one of the questions then analyse how many of employee who left were doing overtime for this i used pie chart to show the proportion of which were doing and which were not first i made a measure for employees who left using DAX's CALCULATE counting the number of persons yes in attrition column then used **overtime** column to make two categories "Yes" or "No" after puting both of them into a pie visual we get that more than half of the employees who left were doing overtime. after this question done going to how are each department's condition on attrition for this i decided to show it in a line chart which will visualise trend in all three departments of **Attrition rate** 

# SHARE 
# ACT



