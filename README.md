# 5d-ds-course_2023
Data Science with Python course. It is meant to be developed in 5 days, counting
with 2 hours a day. It is divided in theory, workshops and a hackathon. The 
practical sessions are developed using jupyter notebooks, specifically colab 
notebooks from Google.

## Prerequisites
This course is developed in Python. A beginners level is required, but
advanced knowledge of the language is recommended. 

Regarding Hardware, the course needs a __Google account with Drive__ and access 
to __a web browser__.

## Content
The course is meant to superficially cover most common packages used in Data 
Science for exploratory data analsysis (EDA), loading data, creating models 
and displaying results: glob, Pandas, Numpy, Scipy, Scikit-Learn, Tensorflow, 
Keras, Matplotlib and Pillow. Other libraries fall outside the scope the 
course.

The course consist of 4 sessions:
1) __Data Science Theory__: It is based on pdf slides. It starts with some generic
definitions, moving to the core of Data Science (DS) concepts answering the what, who,
why, when and how to use DS.
2) __Machine Learning (ML) classic algorithms__: This is the first workshop. 
It covers:
   - Connecting to Google Drive from Colab.
   - Loading a Dataset with Pandas.
   - Doing a brief exploratory data analysis of the data.
   - Preparing the data: normalization/standardization and splitting.
   - Creation of models to predict different variables.
   - Creation of dummies for categorical variables.
3) __Neural Networks (NN)__: It contains a small PDF with a brief explanation of how
a NN works. Then it gets to the jupyter with the following content:
   - NNs to approximate a linear function.
   - NNs to approximate a non-linear function.
   - NNs as a binary classifier of images.
   NOTE: The dataset for this exercise is missing because images were too heavy for a 
   github repo.
6) __Hackathon__: A competitive session to close the course.
   - The students are divided into groups of around 5.
   - The challenge will be based on: 
     - Getting certain kind of data.
     - Having an internal brainstorming with ideas of what is possible.
     - Preprocessing the data.
     - Creating models.
     - Evaluating the models.
   - Different number of points are assigned to the groups depending on the results
   of every step, the winner is the team with the highest amount of points.

## Recommended usage
Clone the repo or download it to your machine. Upload it to Google drive with the 
same folder structure. From Google Drive, if colab notebooks are clicked, they will
be open (you many need to give some permissions from your account) in your browser. Then
it is just following the instructions of every cell.

All cells start with either an exercise number or the indication "### Do not modify this 
cell, not an exercise". The places where code needs to be added are surrounded by a single # 
in the first type of cell.