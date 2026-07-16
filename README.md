
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

1. How other developers suggested breaking into the field (what education to pursue)?
2. What factors about an individual contributed to salary?
3. How bias played a role in the suggestions of developers for how to break into the field?
4. What was the state of bootcamps for assisting individuals with breaking into developer roles?
5. How were bootcamps assisting with increasing diversity in tech careers?

The full set of files related to this course are owned by Udacity, so they are not publicly available here.  However, you can see pieces of the analysis here.  This README also serves as a template for students to follow in creating their own project README files.


## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

### BootcampStats.ipynb

This is a notebook that gives an overview of job prospects and salaries for graduates of a Bootcamp. It gives insight into the time it took before getting a developer job, the amount of diversity in the Bootcamp, and the salaries the Bootcamp graduates are earning in their developer jobs.

### HowToBreakIntoTheField.ipynb

It analyses survey responses on methods to start a developer career. This document shows how many established developers would advise one method or another in those listed in the survey. It also highlights the responses of developers with a higher salary or higher job satisfaction. Finally, it plots how much each method is recommended on average by developers who hold at least a Master's degree and those who do not have one.

### Salary.ipynb

In this notebook, a linear regression model is trained to predict salary based on the following features: career satisfaction, the number of hours worked every week, job satisfaction, and Stack Overflow satisfaction. It also treats different methods of dealing with null values and which one gives an optimal model.

### Salary_ML.py

This is a final draft of the modeling that takes data collected from the responses of a survey, cleans it, and then finds the best model to predict salaries.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 

