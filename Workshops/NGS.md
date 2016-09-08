---
layout: workshop
instructor: "Jenny Wu"
TA: 		
title: 		Next Generation Sequencing Data Analysis
room:		DBH 4011
humandate:	Oct 20, 2016
humantime:	9:00am - 5:00pm
workshop-repo: https://github.com/UCIDataScienceInitiative/IntroR_Workshop 
permalink: Workshops/NGS/
---

## Introduction

This course provides an introduction to the fundamentals of the R language and its applications to data analysis.

In this course, you will learn how to program in R and how to effectively use R for data analysis. The course covers introduction to data/object types in R, reading data, creating data visualizations, accessing and installing R packages, writing R functions, fitting statistical models including regression models and performing statistical tests including t-tests and ANOVA. Practical examples will be provided during the course.

**Who:** The course is aimed at graudate students and other researchers from non-ICS schools. **You don't need to have any previous knowledge of the tools that will be presented at the workshop.**

**Requirements:** Participants must bring a laptop with a few specific software packages installed (see [Pre-Workshop Instructions](#Instructions)). 

**Prerequisites:** Some programming experience is recommended. 

**Contact**: Please mail [hstrong@uci.edu](mailto:hstrong@uci.edu) for more information.

* * *



## <a name="Schedule"></a>Tentative Schedule

| Time	       	|           	|
| ------------- |:-------------:|
| 9:00-10:30   | Session 1		|
| 10:30-12:30   | Session 2   		|
| 12:30-1:00	| Lunch			|
| 1:00-2:30		| Session 3 |
| 2:30-2:45		| Break			|
| 3:00-500	| Session 4 |

* * *



## <a name="Syllabus"></a>Syllabus

* Data Types in R
* Control Structures and Functions
* Statistical Distributions in R
* Exercises: Basic Data Exploration
* Statistical Analysis in R
* Plotting and Data Visualization in R
* Data visualization & Statistical Analysis

* * *


## <a name="Instructions"></a>Pre-Workshop Instructions

### Step 1: Download and install R
First, visit The R Project for Statistical Computing's website through <https://www.r-project.org/>. Click on "CRAN" under the Download section on the left-hand side of the page. Then, click on any of the nearby websites under the USA section near the bottom of the page. For example, the link from the University of California, Berkley, CA or University of California, Los Angeles, CA are both fine. Download R for your platform (Linux, Mac, or Windows).


### Step 2: Download and install RStudio
RStudio is a set of integrated tools designed to help you be more productive with R; it is known to be more user-friendly. You will be doing essentially all of your programming in RStudio. To download RStudio, go to <https://www.rstudio.com/products/rstudio/download/>. Download the installer for your platform under "Installers for Supported Platforms".

### Step 3: Installing packages
After installing R and RStudio, open RStudio. Not all functions have been installed in R, so utilizing certain functions requires you to install a package and ``open'' that package every time you open a new R session. There are two ways to install packages in RStudio.

* Method 1: Find your console (for first-time R users, the console is located at the bottom-left of RStudio's interface). Then type the following code and press Ctrl + Enter or Run (the quotation marks are needed between the package name):

```
R> install.packages("PackageName", dependencies = TRUE)
```

* Method 2: On RStudio's taskbar, click on "Tools" and then "Install Packages..." Afterwards, put down the name of the package(s) you wish to install and click install.

Before the workshop begins, please install the following packages: ggplot2. See below for example command.

```
R> install.packages("ggplot2", dependencies = TRUE)
```
<script type="text/javascript" src="https://uci-oai.formstack.com/forms/js.php/intro_to_r_05_31_16"></script><noscript><a href="https://uci-oai.formstack.com/forms/intro_to_r_05_31_16" title="Online Form">Online Form - 5/31/16 - Intro to R</a></noscript>


