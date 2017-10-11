# Exploratory Data Anlysis with R

## Paul Intrevado

Welcome to Exploratory Data Anlysis with R (MSAN 593), a required course in the completion of the MS Analytics degree at the University of San Francisco. Find the syllabus and course notes in this repository.

[**Syllabus**](https://github.com/paulintrevado/msan593/blob/master/syllabus.pdf)

## Course Learning Outcomes

By the end of this course, you will be able to

- Proficiently wrangle, manipulate, and explore data using the R programming language
- Utilize contemporary R libraries including *ggplot2*, *tibble*, *tidyr*, *dplyr*, *knitr*, and *stringr*
- Visualize, present, and communicate trends in a variety of data types
- Communicate results using R markdown and R Shiny
- Formulate data-driven hypotheses using exploratory data analysis and introductory model building techniques

## Course Overview

### Assessment

The focus of this course will be to provide you with the basic techniques available for making informed, data-driven decisions using the R programming language. This is *not* a statistics course, but will provide you the intuition to make hypotheses about complex questions through visualization, wrangling, manipulation, and exploration of data. The course will be graded based on the following components:

- **Attendence** (20%): You will lose 2% of this grade for every course you miss.
- **Assignments** (40%): You will be assigned a computational assignment to be completed using RStudio and the package *knitr* regularly throughout class. 
- **Case Studies** (20%): You will be assigned applied case studies throughout the class that are to be completed using RStudio.
- **Final Project** (20%): The final project will be a computational case study that brings together the techniques learned throughout the semester. The description for this project will be provided towards the mid point of the semester.
- **Extra Credit** (+5%): Create a *well-organized* database of *all* R functions that you use throughout the semester. These include those mentioned in lectures, those introduced in homework, etc. Along with each function, give a brief description that details the use of the function. Also, organize these functions into categories according to their use.

**Introduction**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | [Introduction - History of Data Science](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%201%20Introduction.pdf) | [Ch. 1 What is Data Science?](https://www.safaribooksonline.com/library/view/doing-data-science/9781449363871/ch01.html)| [HW 1](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Assignments/Assignment1.pdf) | Thursday, 8/24| |
 | [R and RStudio](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%202%20R%20and%20RStudio.pdf)| | [HW 2](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Assignments/Assignment2.pdf) | Tuesday, 8/29| [My First Code](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/My_First_Plot.R) |
 | [R Packages and RMarkdown](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%203%20R%20Markdown.pdf)   | | [HW 3](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Assignments/Assignment3.pdf)| Tuesday, 9/5 | [My First Knit](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/Knit_Example.Rmd) |
  
  
 **Data Structures in R**
  
 | Topic | Reading | Assignment | Due Date | In Class Code |
  | :---  | :---:  | :---:  | :---:  | :---: |
  | [Vectors, Matrices, and Arrays](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%204%20Data%20Structures%20I.pdf) | | [HW 4](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Assignments/Assignment4.pdf)| Tuesday, 9/12| [[Data Structures I]](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/Data_Structures1.R) [[Data Structures II]](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/Data_Structures2.R)|
  | [Lists and Data Frames](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%205%20Data%20Structures%20II.pdf) | [Ch. 20 in R for Data Science](http://r4ds.had.co.nz/vectors.html)| | | [Data Structures III](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/Data_Structures3.R) |
  | [Tibbles](http://r4ds.had.co.nz/tibbles.html)| [Ch. 10 in R for Data Science](http://r4ds.had.co.nz/tibbles.html)| [HW 5](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Assignments/Assignment_Tibbles.pdf) | Tuesday, 9/26 | [Tibbles](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/tibbles.R) |
  | [String Analysis](http://r4ds.had.co.nz/strings.html)|[Ch. 14 in R for Data Science](http://r4ds.had.co.nz/strings.html) | [HW 6](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Assignments/Assignment_Strings.pdf)| Thursday, 9/28| [String Analysis I](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/Strings1.R)|
   | [String Analysis 2](http://r4ds.had.co.nz/strings.html)|[Ch. 14 in R for Data Science](http://r4ds.had.co.nz/strings.html) | [HW 7](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Assignments/Assignment_Strings2.pdf)| Thursday, 10/5| [String Analysis II](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/Strings2.R) |
  | [Factors](http://r4ds.had.co.nz/factors.html) | [Ch. 15 in R for Data Science](http://r4ds.had.co.nz/factors.html)| | |
  
  
  **Data Wrangling**
  
   | Topic | Reading | Assignment | Due Date | In Class Code |
   | :---  | :---:  | :---:  | :---:  | :---: |
   | [Input and Output](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%206%20Input%20and%20Output.pdf) | | | |
   | [Wrangling Data](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%2010%20Wrangling%20Data.pdf) | | | |
   
   
  **Plotting in R**

 | Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | [Plotting in R](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%207%20Plotting%20in%20R.pdf) | | | |
 
 
 **Programming**
 
 | Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | [Control Flow](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Lectures/Functional%20Programming%20I.pdf)| | | | 
 | [Writing Functions](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Lectures/Functional%20Programming%20II.pdf)| | | | 
 | [Functionals](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Lectures/Functional%20Programming%20III.pdf)| | | | 
 
 **Statistical Modeling in R**
 
 | Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | [Intro to Statistical Modeling in R](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Lectures/Lecture%2011%20Intro%20to%20Statistical%20Modeling.pdf) | | | | 


### Case Studies
| Case Study | Data | Date |
|:--- | :---  | :---:  |
|[CS 1: Beer Review Analysis](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Code_Demonstrations/Case%20Study%201/Beer_Analysis.pdf) | [beerdata.RData](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Code_Demonstrations/Case%20Study%201/beer.data.RData) | September 12th, 2017| 
|[CS 2: Text Mining](https://github.com/jdwilson4/Intro-Data-Science/blob/master/Code_Demonstrations/Case%20Study%202/CaseStudy2.pdf) | [[tweets.csv]](https://raw.githubusercontent.com/jdwilson4/Intro-Data-Science/master/Data/tweets.csv); [[stateoftheunion1790-2012.txt]](https://raw.githubusercontent.com/jdwilson4/Intro-Data-Science/master/Data/stateoftheunion1790-2012.txt)| September 28th, 2017|


### Final Project
| Description | Due Date |
|:--- | :---  |
|[Project Signup] | |
|[Final Project Description](https://github.com/jdwilson4/Intro-Data-Science-2017/blob/master/Assignments/Final_Project.pdf) | 
