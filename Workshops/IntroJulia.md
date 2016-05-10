---
layout: workshop
instructor: "Chris Rackauckas"
TA: 		
title: 		Introduction to Julia
room:		DBH 3011
humandate:	May 24, 2016
humantime:	9:00am - 1:00pm
workshop-repo: https://github.com/UCIDataScienceInitiative/IntroR_Workshop 
permalink: Workshops/IntroJulia/
---

## Introduction

Julia is a relatively new language which has been making waves in the scientific community due to its ease of use as a scripting language combined with its ability to produce programs with comparable runtimes to C/Fortran. For this reason, Julia is situated is fast becoming a major language in high-performance and “big data” computing. However, the current state of the Julia ecosystem can be intimidating to much of its target audience, which is both high-level scriptors (using MATLAB/Python/R) all the way to developers of high-performance libraries (using C/Fortran). This workshop is aims to introduce both users of scripting languages and advanced programmers to the Julia ecosystem, and explore details about the Julia language which can help produce efficient and readable code. The goal of the workshop is for students to understand where Julia can be applied and be well-equipped to start using Julia in their own research. Students will learn about the current state of Julia development (IDEs, documentation, where to get help), how to write efficient code by understanding some of Julia's internals via small projects, solve problems using advanced Julia features (metaprogramming, multiple-dispatch, etc.), and learn workarounds to common issues newcomers face (scoping problems, type conversions, etc.). Near the end of the workshop, participants will break out into groups to solve problems which mirror research problems in data science and scientific computing. 

**Who:** Reserchers who understand the fundamentals of some other scripting language and want to learn how to utilize Julia. **You don't need to have any previous knowledge of the tools that will be presented at the workshop.**

**Requirements:** Participants must bring a laptop. Ideally a few specific software packages should be installed beforehand (see [Pre-Workshop Instructions](#Instructions)). 

**Prerequisites:** Previous experience with a scripting language (R/Python/MATLAB etc.).

**Contact**: Please mail [crackauc@uci.edu](mailto:crackauc@uci.edu) for more information.

* * *



## <a name="Schedule"></a>Tentative Schedule

| Time	       	|           	|
| ------------- |:-------------:|
| 8:00-9:00   | Installation Help Session	|
| 10:00-11:00   | Basic Introduction		|
| 11:00-12:00	| Julia Fundamentals			|
| 12:00-1:00		| Breakout into Project Groups |


* * *



## <a name="Syllabus"></a>Syllabus

* Basic Introduction
  * Why Julia? When to choose Julia?
  * Installing/Building Julia, Setting up an IDE
  * Package Management and Github
  * Basic usage: control statements, types, and functions
  * Where to get help: documentation, message boards, etc.
  * Plotting and Data Visualization in R
  * Data visualization & Statistical Analysis
* Fundamentals of Julia
  * Differences from other common languages
  * Linear algebra
  * Data-oriented programming
  * Macro meta-programming
  * Levels of parallelization
  * De-vectorization, SIMD, threading
  * Named functions
  * Subscoping
  * LLVM
* Guided Projects
  * Mathematical Modeling
  * Data Visualization
  * Multi-node HPC ("Julia's MPI")
  * Investigating LLVM
  * Modules and Package Development
  * Langugage Bindings
  * Data Saving and Serialization

* * *


## <a name="Instructions"></a>Pre-Workshop Instructions

Installing Julia beforehand is not required, though highly recommended. Attendees may wish to install the Julia/Atom IDE before the workshop, though be advised this may not be easy <https://github.com/JunoLab/atom-julia-client/tree/master/manual> . Help for doing so can be found at the UCI Data Science Initiative Gitter <https://gitter.im/UCIDataScienceInitiative/Julia> and the JunoLab Gitter <https://gitter.im/JunoLab/Juno>.  Before the workshop we will have a one-hour installation session for users who are having issues.
