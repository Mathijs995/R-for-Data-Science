# R for Data Science
This repository contains all the links to the slides, Google colab notebooks and other resources used in the R for Data Science course taught in collaboration with Turing Students Rotterdam from October 2019 until November 2019. This entry-level R course teaches students, with or without prior programming experience, the fundamentals of the R programming language and the required knowledge to get started in data science. Topics include data types, functions, algorithms, data visualisation and machine learning.  Problem sets are designed to prepare EUR students for applying R in their domains of interest. After this course students should have basic understanding of programming and be ready to dive into the world of data science.

## Course Setup and Rules
The course consists of two parts. The first four weeks are dedicated to diving into the R programming language and a number of core data analytics methods. The last two weeks are dedicated for a data science challenge inspired by real-world problems in collaboration with [Cognizant](https://www.cognizant.com/nl-nl/).

### Practical Information
There are lectures on **Tuesdays** and **Thursdays** from **18.00** until **20.00**. The Google calendar with the schedule of the course is available [here](https://calendar.google.com/calendar/r/month/2019/11/1?cid=dHNvY2lldHkuaW9fNWo4dTlqdGYxbzFpZG9yanZtZzVyb29mMm9AZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ). 80% attendance is mandatory and please inform us *before* class when you are not attending a lecture through a private message on Slack. In case you do not meet the attendance requirement, you are not eligable for the course certificate.

For communication related to the course, we are using [Slack](https://tstudents-rotterdam.slack.com/). If you have not done so already, please register your account and check out the channels. On Slack you can talk to the staff behind the course and to your fellow students in either the (public) group chat or using direct (private) messages.

### Teaching Philosphy
At Turing Society, we believe in the power of diversity. People are unique and the best results are obtained by combining different insights and approaches. Therefore, all our courses are open to everyone; it does not matter whether you are a bachelor student, master student, working professional or in a transition period.

Furthermore, we believe learning is most effective when you *learn together*. The focus should be on *learning by doing*, *learning by explaining concepts and solutions to your fellow students* and *learning by means of discussion*. You will see that the journey becomes a lot more enjoyable when you go through it together! In fact, all our staff is helping on voluntary basis because we love learning with you guys.

Please interrupt the course at any moment when you have questions, suggestions or feedback. We are always looking to improve our courses and need you help with this. If you prefer providing your input over other channels, feel free to do this as well. It does not matter who at Turing Students Rotterdam you approach, we all want to hear your ideas and hope to use these to improve the quality of our courses and events.

### Rules
Next to the attendance requirements, we have to set some rules in order to efficiently facilitate learning. There are homework assignments that have to be completed to a sufficient standard to pass the course. If you ever have questions, feel free to reach out to your fellow students or to us over Slack. Note that homework *may* be done in collaboration (in fact, we highly encourage it). However, copying homework is *strictly forbidden*. The goal of this course is for you to improve your coding skills. Copying material from other students is a waste of both your time and our time. Please hand in assignments later and ask questions when you get stuck instead of copying solutions. We are here to help you and do not have any incentives to act otherwise.


## Session 1 - Thursday 3 October
Session 1 covers the core building blocks of programming languages and the corresponding syntax in R. The Google colab notebook [Week 1 - Lecture 1.1](https://colab.research.google.com/drive/1iJjLO2VvS583ZTOCs2IMy_0bkZpMDSTO) is used in this session. Additionally, the slides for the introduction of the course can be downloaded [here](https://github.com/Mathijs995/R-for-Data-Science/raw/master/R%20for%20Data%20Science%20-%20Lecture%201.pdf).

### Material Covered
- Introduction to the R Programming Language
- Programming Environments
- R Fundamentals
  - Variables
  - Workspaces and files
  - Data Types
  - Operators

### Homework
#### Due date: Tuesday 8 October 18.00
*Readings:* Sections 1, 2, 3.1 - 3.4 in the [Week 1 - Lecture 1.1](https://colab.research.google.com/drive/1iJjLO2VvS583ZTOCs2IMy_0bkZpMDSTO) notebook.

## Session 2 - Tuesday 8 October
Session 1 covered the reasons why data analytics skills are becoming more valuable, the reasons to learn R and the core fundamentals of R. Session 2 continues with collections of variables and subsetting. The following Google Colab notebook is used for this session: [Week 2 - Lecture 2.1](https://colab.research.google.com/drive/1lzvpTw5DVR4-ekCxd9_tn0F0e9QncSof).

### Material Covered
- Data structures
    - Vectors
      - Atomic vectors
      - Lists
    - Attributes
    - Matrices and arrays
    - Data frames

### Homework
#### Due date: Thursday 10 October 18.00
*Readings:* Section 3.5 in the [Week 1 - Lecture 1.1](https://colab.research.google.com/drive/1iJjLO2VvS583ZTOCs2IMy_0bkZpMDSTO) notebook and Section 1 of the [Week 2 - Lecture 2.1](https://colab.research.google.com/drive/1lzvpTw5DVR4-ekCxd9_tn0F0e9QncSof) notebook.

## Session 3 - Thursday 10 October
Session 2 covered data structures and sessions 3 continues with subsetting and controlling the flow of our code. The Google colab notebook for this lecture is [Week 2 - Lecture 2.2](https://colab.research.google.com/drive/1FQICEcnG3o-rVtM8b67f7PgwccGqGBln).

### Material Covered
- Subsetting
    - Data structures
      - Atomic vectors
      - Lists
      - Matrices and arrays
      - Data frames
    - Subsetting operators
    - Subsetting and assignment
- Control flow
  - Conditional statements
  - Loops
  
### Homework
#### Due date: Tuesday 14 October 18.00
*Readings:* Section 2 of the [Week 2 - Lecture 2.1](https://colab.research.google.com/drive/1lzvpTw5DVR4-ekCxd9_tn0F0e9QncSof) notebook and the [Week 2 - Lecture 2.2](https://colab.research.google.com/drive/1FQICEcnG3o-rVtM8b67f7PgwccGqGBln) notebook.

*Note:* Try to solve as many questions as possible in the notebooks. Please do not spend more than two hours this week trying to solve the exercises. The exercises are good practice for coding in general but not essential for doing data analytics.

## Session 4 - Tuesday 15 October
Session 4 covers RStudio, functions, packages and the apply family. The Google colab notebook for this lecture is [Week 3 - Lecture 3.1](https://colab.research.google.com/drive/1R9FuON0gUEIGEhuMNAV4B4ZvZHne7thK).

### Material Covered
- RStudio
- Functions
  - Function Definition
  - Built-in Functions
  - User-defined Functions
  - Arguments with default values
  - Ellipsis argument
  - Functions - best practices
- Packages
  - R Packages
  - Repositories
  - How to Install a R Package
  - Updating, Removing and Checking Installed Packages
  - Loading Packages
  - Choosing the Right R Package
- Apply family
  - The apply() Function
  - The lapply() Function
  - The sapply() Function
  - The rep() Function
  - The mapply() Function
  
### Homework
#### Due date: Tuesday 29 October 18.00
*Readings:* [Week 3 - Lecture 3.1 notebook](https://colab.research.google.com/drive/1R9FuON0gUEIGEhuMNAV4B4ZvZHne7thK)

*Note:* Try to solve as many questions as you can in the notebook, Please do *not* spend more than two hours to solve the questions. Again, the exercises are good practice but not essential for data science in general.

## Session 5 - Thursday 17 October
What better way to start with data science than to start with plotting? In this session, we go over ggplot2, the most popular package for plotting in R. The Google colab notebook for this lecture is [Week 3 - Lecture 3.2](https://colab.research.google.com/drive/1ZTBm6aG4gozuBgr-m2v5ZDsWH3banj9h).

### Material Covered
- ggplot2
  
### Homework
#### Due date: Tuesday 29 October 18.00
*Readings:* [Week 3 - Lecture 3.2 notebook](https://colab.research.google.com/drive/1ZTBm6aG4gozuBgr-m2v5ZDsWH3banj9h)

## Session 6 - Tuesday 22 October
The Google colab notebook for this lecture is [Week 4 - Lecture 4.1](https://colab.research.google.com/drive/1am1CUGg1n4i187RwTyv0KUL4d5s0N1gf).

### Material Covered
- Exploratory Data Analysis
- Rule-Based Learning
- (Decision Trees)
  
### Homework
#### Due date: Tuesday 29 October 18.00
*Readings:* [Week 4 - Lecture 4.1](https://colab.research.google.com/drive/1am1CUGg1n4i187RwTyv0KUL4d5s0N1gf)

## Session 7 - Thursday 24 October
The Google colab notebook for this lecture is [Week 4 - Lecture 4.2](https://colab.research.google.com/drive/1_btbFkCvG1uNptt_m9IF22L_-M_M1kv_).

### Material Covered
- Decision Trees
- k-means
- Naive Bayes Classifier
  
### Homework
#### Due date: Thursday 31 October 18.00
*Readings:* [Week 4 - Lecture 4.2](https://colab.research.google.com/drive/1_btbFkCvG1uNptt_m9IF22L_-M_M1kv_)

## Session 8 - Tuesday 29 October
The presentation for this lecture is [R for Data Science - Analytics Presentation](https://github.com/Mathijs995/R-for-Data-Science/raw/master/R%20for%20Data%20Science%20-%20Analytics%20Presentation.pdf).

### Material Covered
- Overview of AI and Machine Learning
- Introduction to Regression Analysis
  
### Homework
No homework.

## Session 9 - Thursday 31 October
The last session before the final case is dedicated to work on the [R for Data Science - Homework Challenge](https://colab.research.google.com/drive/1_btbFkCvG1uNptt_m9IF22L_-M_M1kv_).

### Homework
#### Due date: Sunday 17 November 23.59
*Hand in:* [R for Data Science - Homework Challenge](https://colab.research.google.com/drive/1_btbFkCvG1uNptt_m9IF22L_-M_M1kv_). Note that you are allowed to hand in the challenge individually or in pairs. Feel free to collaborate but *do not* copy solutions.

## Session 10 - Tuesday 5 November
Time to put your skills to test and work on the challenge in collaboration with [Cognizant](cognizant.com)! Here is the link to the first notebook: [R for Data Science - Cognizant Case - Session 1](https://colab.research.google.com/drive/1tSd1DsHLK11ijuv4HPrjeWMSo1nHl0wX).

### Homework
#### Due date: Thursday 7 November
Attempt to solve the challenges in the final case notebook [R for Data Science - Cognizant Case - Session 1](https://colab.research.google.com/drive/1tSd1DsHLK11ijuv4HPrjeWMSo1nHl0wX). Please try your best to solve the problems and focus on how you should go about solving the problems. Do not worry to much if you get stuck with certain parts of the assignment.

## Session 11 - Thusrday 7 November
Now that the basis has been set, we can continue by deploying models to gain insights from our data. Here is the link to the second notebook: [R for Data Science - Cognizant Case - Session 2](https://colab.research.google.com/drive/1vlzOjxD4LDXaSWd0AsSF4v0-6zRH8Hdr).

### Homework
#### Due date: Sunday 17 November
Attempt to solve the challenges in the final case notebook [R for Data Science - Cognizant Case - Session 2](https://colab.research.google.com/drive/1vlzOjxD4LDXaSWd0AsSF4v0-6zRH8Hdr). Please try your best to solve the problems and focus on how you should go about solving the problems. Do not worry to much if you get stuck with certain parts of the assignment.
