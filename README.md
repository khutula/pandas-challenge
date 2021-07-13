# GT Bootcamp Pandas Homework: PyCitySchools

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Technologies](#technologies)
4. [Files](#files)
5. [Analysis](#analysis)

<a name="introduction"></a>
### Introduction
As the new Chief Data Scientist for the school district, I will be responsible for helping the school board develop strategic, data-driven decisions about school budgets and priorities.  My first task is to analyze the math and reading standardized test scores from every stduent and find trends in the data.

<a name="objectives"></a>
### Objectives
Write a Python script using Jupyter Lab that summarizes school and student data by:
* District Summary
* School Summary
* Top Performing Schools (By Percent Overall Passing)
* Bottom Performing Schools (By Percent Overall Passing)
* Math Scores by Grade
* Reading Scores by Grade
* Scores by School Spending
* Scores by School Size
* Scores by School Type

<a name="technologies"></a>
### Technologies
This project uses: 
* Python Version 3.6.13
* Jupyter Lab Version 2.2.6

<a name="files"></a>
### Files
* [students_complete.csv](PyCitySchools/Resources/students_complete.csv): raw data file for all general student data
* [schools_complete.csv](PyCitySchools/Resources/schools_complete.csv): raw data file for all general school data
* [PyCitySchools.ipynb](PyCitySchools/PyCitySchools.ipynb): Jupyter Lab file with data analysis and summary charts
* [Jupyter Notebook Viewer of PyCitySchools.ipynb](https://nbviewer.jupyter.org/github/khutula/pandas-challenge/blob/main/PyCitySchools/PyCitySchools.ipynb): use this link to view the Jupyter Lab file in a friendly viewer version. 

<a name="analysis"></a>
### Analysis

The most easily observable trend of this data is that the Charter schools scores and passing percents surpass District schools across the board. This can be seen in the differences on the Scores by School Type chart as well as Top Performing Schools vs Bottom Performing Schools. The Top 5 Performing Schools (by overall passing percent) are all Charter schools, while the Bottom 5 are all District schools.

Additionally, we can see that Small & Medium sized schools have superior scores and passing percentages in comparison to Large sized schools.  Interestingly, all but one Charter school falls into Small or Medium, while Large is all District schools and one Charter school.

The most interesting trend of this data set is that Spending Range (Per Student) is strongly inversely related to overall passing percent. This finding deserves an investigation because logic would dictate that the Spending Range and Passing Percent would be posivitely correlated. Is money being unwisely spent in some schools? Do Charter schools get funding from alternate sources that don't count into their Total Budget? 