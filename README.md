# Data in the Wild: An Introductory Data Science Course for the Life Sciences

## 🐧 About
This is a repository for the code, materials and data for *Data in the Wild* (WFSC 223), which was designed to introduce life science majors to basic programming, statistics, and machine learning. This course was developed by Drs. Katy Prudic, Jeff Oliver, Keaton Wilson, and Ellen Bledsoe at the University of Arizona. This was taught in pilot form at the University of Arizona in Spring 2020 as *Settlers of Antarctica*, and places students in the roles of Antarctic researchers navigating issues that may arise during their time in the Frozen Land. They will be tasked to use what they have learned to answer questions such as what is causing their team's stomach illness, where is the safest area to catch fish, and how to optimize a road with the least impact on the Antartic ecosystem.

## 🦭 Module Descriptions

The following is a summary and outline of each section covered in this course. When this course was piloted there were five modules presented in the [outline](https://docs.google.com/document/d/1g7sM4RWGn4EkhDRX9qXeeAMLkvbZGqJWIfAlDpMPYHM/edit?usp=sharing), but of course due to the pilot nature of the course (and complications with the COVID-19 pandemic) only the first four modules were developed and administered.

- _**Module 1: Mission Antarctica!**_ <br /> A new effort to establish a permanent, sustainable colony in Antarctica is being launched. Students are introduced to the field of data science and the application (RStudio, RMarkdown, Jupyter Notebooks) and programming language (R, Python) used in the course.
  - **1.1:** Introduction to RStudio
  - **1.2:** Introduction to Coding
  - **1.3:** 2-dimensional Data and the `tidyverse` 

- _**Module 2: Good food gone bad.**_ <br /> There is a food poisoning outbreak among team members. Students use data visualization to determine where the problem lies (fish, not plants) and simulations to determine the root of the problem (fish tank density, not fish tank temperature).
  - **2.1:** Introduction to Descriptive Statistics and Data Visualization
  - **2.2:** Writing Functions
  - **2.3:** Plotting with `ggplot2`
  - **2.4:** A Visualization Primer
  - **2.5:** Sick Fish
  - **2.6:** Exploring `geom` Functions
  - **2.7:** Wrap-Up

- _**Module 3: Follow that seal!**_ <br /> The fish tanks need to be restocked, but we want to avoid fishing in places with high leopard seal density, so we track the seals. However, the radio collars on leopard seals are failing and there is a deadly conflict between fish collectors & seals. The collars come from two different manufacturers, but we need to tell how the collars are failing (days to recharge, not signal distance) and how to classify collars of unknown provenance.
  - **3.1:** Leopard Seals
  - **3.2:** T-Test
  - **3.3:** Comparing (Multiple) Means
  - **3.4:** Combining Data (Joins and Binds)
  - **3.5:** K-Nearest Neighbor

- _**Module 4: March of the penguins.**_ <br /> A new road is needed to access fishing sites with low leopard seal density. There are several possible routes, but we want to avoid crossing through Gentoo penguin nesting grounds. Students will build models to determine predictors of nesting success, first with bootstrapping for confidence intervals, then with linear regression.
  - **4.1:** Roads and Regressions
  - **4.2:** Multiple Regression
  - **4.3:** Using Functions to Automate Tasks

## 🌾 Course Materials

A sample syllabus used at the University of Arizona can be found here: [Sample Course Syllabus](https://docs.google.com/document/d/1zXAlG_WbsjshQSXssWDPeRpqy8q_uNjOIe1WLTPPJBk/edit?usp=sharing). The materials used in this course are accessible under the `modules` folder. The contents of each module folder (e.g. `module_1`), with the exception of the folder containing the final assignment, are as follows:

- _**assets:**_ <br /> Images and PDFs used in lectures.

- _**assignments:**_ <br /> Assignments associated with each module. All assignments are R Markdown files that the students are expected to render and submit as a PDF. Also under this folder is a sub-folder named `assignment_keys`, which contains the student and instructor versions of the answer keys. The student version (those ending in _Student_Key) only shows what would result from the expected code. The student keys _do not_ show the code that needs to be written to achieve the correct answer, but it is offered to students as a hint towards what they should be outputting. The instructor version (those ending in _Instructor_Key) shows the code that should more or less be written in addition to the answers outputted.

- _**data:**_ <br /> Data sets used in the lectures and assignments. The data are all .csv files.

- _**discussions:**_ <br /> Discussions that can be assigned in addition to the assignments. These ask students thought-exercising questions such as how data plays a role in decision-making, the impact of incorrect information, and the applications of data science. The students are expected to cite sources to defend their comments, giving them an opportunity to practice engaging with literature.
 
- _**exams:**_ <br /> Exams and study guides of what students are expected to know at the conclusion of each module.

- _**lessons:**_ <br /> There are code-along formats of the lessons for the students (those _not_ ending in _Instructor), which contain the same text as the instructor version (ending in _Instructor) but with empty code blocks. The student version assumes that the instructor is live-coding with the students following along and typing (into their own document) what the instructor is presenting. There are PDF versions of the instructor version to print out and use as a guide for what to code with the students.

- _**scripts:**_ <br /> The code used to generate the data in the `data` folder for that module.

