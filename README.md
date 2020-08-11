## **Investigate_TMDb_Movies** 

---
###### Project introduction

In this project, you will analyze a dataset and then communicate your findings about it. You will use the Python libraries NumPy, pandas, and Matplotlib to make your analysis easier.

---

<p align = "center">
<img src = "./images/mat.png" />
</p>

---
## What do I need to install?
```
pandas
NumPy
Matplotlib
csv

```
```
   pip install (name libraries)
   
```
---


### Table of Contents
---

- [Overview](#Overview)
- [steps of project](#steps-of-project)
- [dataset](#dataset)
- [concolusion](#concolusion)
- [end](#end)

---
## Overview :point_left:

In this project, you'll go through the data analysis process and see how everything fits together. Later Nanodegree projects will focus on individual pieces of the data analysis process.

You'll use the Python libraries NumPy, pandas, and Matplotlib, which make writing data analysis code in Python a lot easier! Not only that, these are sought-after skills by employers!


---

## What will I learn?

###### After completing the project, you will:

- Know all the steps involved in a typical data analysis process

- Be comfortable posing questions that can be answered with a given dataset and then answering those questions

- Know how to investigate problems in a dataset and wrangle the data into a format you can use

- Have experience communicating the results of your analysis

- Be able to use vectorized operations in NumPy and pandas to speed up your data analysis code

- Be familiar with pandas' Series and DataFrame objects, which let you access your data more conveniently

- Know how to use Matplotlib to produce plots showing your findings


---

## steps of project

- [Choose Your Data Set](#dataset)
- [data cleaning](#data-cleaning)
- [question about data](#question-about-data)
- [Analyze Your Data](#Analyze-Your-Data)
- [visualize data](#visualize-data)


---

## dataset

Click this link [dataset](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf) to open a document with links and information about data sets that you can investigate for this project. You must choose one of these datasets to complete the project.

###### link TMDb_Movies dataset [click](https://www.kaggle.com/tmdb/tmdb-movie-metadata) 

---

## data cleaning

- drop duplicated
```
   df.drop_duplicates(inplace= True)
```
- fill non value with mean

```
   df.dropna(inplace=True)

```

- fix data format


---

## Analyze Your Data

Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the data[](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf) set options to help you get started.

Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and pandas where they are appropriate!

---


## end :raising_hand:

