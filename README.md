# Introduction to Quantitative Geology (Course 54070) - Spring 2016

## Course meetings
- Mondays 14-16, C108, Physicum (14.3-2.5)
- Wednesdays 14-16, D211, Physicum (16.3-4.5)

## Instructor
- David Whipp
- Office: D430, Exactum
- Email: `firstname.lastname@helsinki.fi`
- Phone: (0)2 941 51617

## Course website
- Main course site: [https://github.com/Intro-Quantitative-Geology](https://github.com/Intro-Quantitative-Geology)
- Moodle page: [https://moodle.helsinki.fi/course/view.php?id=12453](https://moodle.helsinki.fi/course/view.php?id=12453)

## Textbooks
- There are **no required textbooks** for this course. This course uses a wide range of sources for course information and the main textbooks are given below.
- Recommended textbooks (in order of relevance):
    - Zelle, J. (2010) [Python Programming: An Introduction to Computer Science](http://mcsp.wartburg.edu/zelle/python/ppics2/index.html), Second edition. Franklin, Beedle & Associates.
    - Stüwe, K. (2007) [Geodynamics of the Lithosphere](http://wegener.uni-graz.at/publication/books/geodyn2nd/), Second edition. Springer.
    - Braun, J., van der Beek, P. and Batt, G. (2006) [Quantitative Thermochronology: Numerical Methods for  the Interpretation of Thermochronological Data](http://www.cambridge.org/us/academic/subjects/earth-and-environmental-science/geochemistry-and-environmental-chemistry/quantitative-thermochronology-numerical-methods-interpretation-thermochronological-data), First edition. Cambridge University Press.
    - Taylor, J. R. (1997) [An Introduction to Error Analysis: The Study of Uncertainties in Physical Measurements](http://www.uscibooks.com/taylornb.htm), Second edition. University Science Books.
- Optional textbooks:
    - Pelletier, J. (2008) [Quantitative Modeling of Earth Surface Processes](http://www.cambridge.org/us/academic/subjects/earth-and-environmental-science/geomorphology-and-physical-geography/quantitative-modeling-earth-surface-processes?format=HB), First edition. Springer.
    - Trauth, M. H. (2010) [MATLAB® Recipes for Earth Sciences](http://www.springer.com/cn/book/9783642447167), Third edition. Springer.
    - Beazley, D. M. (2012) [Python Essential Reference](http://www.dabeaz.com/per.html), Fourth edition. Addison-Wesley.

## General description of the course
This course aims to:

1. Introduce students to modelling Earth science data and the Python programming language
2. Develop basic programming skills through analysis of common equations used in the Earth sciences
3. Present some common techniques for comparing geologic data to numerical model predictions

## Course format
This course is equally divided between lectures on Mondays and computer-based laboratory exercises on Wednesdays. Monday classes will be divided into two \~45 minute lectures with a short break in the middle of class. Lectures slides will be available on Moodle on the morning prior to each lecture. Laboratory exercises will focus on applying lecture material and developing basic programming skills using the Python language. Typical exercises will involve a short introduction, followed by topical computer-based tasks. At the end of the exercises, you will be asked to submit answers to relevant questions, and possibly related plots and/or Python codes you have written/used. Students are encouraged to discuss and work together on the laboratory exercises, however the laboratory summary write-ups that you submit must be completed individually and must clearly reflect your own work.

## Grading
Course grades will be given using the universal six-level grading scale from 0 to 5. Your grade will be based on (1) six laboratory exercise summary write-ups, and (2) a course project (briefly described below). The weight of each item is given below.
- 50% - Exercise write-ups (6 in total)
- 50% - Final project report

Note: Deadlines for exercise write-ups and the term project are **firm** and given in the schedule on the following pages. Exercise write-ups will be due by the start of lab on the due date. If you anticipate you will not be able to submit any of these items by the given deadline, you should let me know as early as possible and must let me know at least one day in advance. Late write-ups will be marked down 25\% per day late, so please submit it on time.

## Final project
The final project is based on the results you will produce in Exercises 6 and 7. In these exercises, you will modify a Python code to read in a data file, make some basic calculations using some of the equations we’ve discussed earlier in the course and produce a series of plots. The goal of the exercise is to model a geological dataset and use the model to interpret the data. The final project report will involve writing a short paper with the introductory and background material for the data from Exercises 6 and 7, presenting your results in a series of plots with a short section of text and then discussing the meaning of the results. The intent is for you to write a short scientific paper with the same material that would typically be present in a scientific journal article. Details on the final project paper will be given later in the course.

## Course topics by week
*Lecture content, readings and due dates are subject to change*
### Basic concepts of quantitative geology
**14.3 (Lecture)** - (I) What is Quantitative Geology?, (II) Essentials of computing
- Readings: Stüwe, Chapter 1; Zelle, Chapters 1 & 2

**16.3 (Lab)** - Exercise 1: Introduction to Python and NumPy I
- Homework: None

### Dealing with age data: Radioactivity and essential geostatistics
**21.3 (Lecture)** - (I) Common statistical methods in geoscience, (II) What do geochronologic ages mean?
- Readings: Taylor, Chapters 2 & 4

**23.3 (Lab)** - Exercise 2: Introduction to Python and NumPy II
- Homework: Exercise 1 write-up due

### 28.3, 30.3 - NO CLASS (Easter holiday break)

### Hillslope sediment transport and heat transfer: The diffusion equation 
**4.4 (Lecture)** - (I) Natural diffusion: Hillslope sediment transport, Earth’s thermal field, (II) Applying the diffusion equation
- Readings: Stüwe, Chapter 3; Pelletier, Chapter 2

**6.4 (Lab)** - Exercise 3: Uplift and diffusion of the Earth’s surface
- Homework: Exercise 2 write-up due

### Fluvial incision and rock uplift: The advection/wave equation
**11.4 (Lecture)** - (I) Advection of the Earth’s surface: Fluvial incision and rock uplift, (II) Applying the advection/wave equation
- Readings: Stüwe, Chapter 3; Pelletier, Chapter 4

**13.4 (Lab)** - Exercise 4: River profile calculations
- Homework: Exercise 3 write-up due

### Viscous flow of rock and ice: (Non-)Newtonian flow equations
**18.4 (Lecture)** - (I) Rocks and ice as viscous materials, (II) Equations of viscous flow
- Readings: Stüwe, Chapter 5; Pelletier, Chapter 6

**20.4 (Lab)** - Exercise 5: Glacier mechanics
- Homework: Exercise 4 write-up due

### Quantitative thermochronology: Linking ages to processes
**25.4 (Lecture)** - (I) Basic concepts in thermochronology, (II) Low-temperature thermochronology
- Readings: Braun et al., Chapters 1-3

**27.4 (Lab)** - Exercise 6: Predicting thermochronometer ages I
- Homework: Exercise 5 write-up due

**2.5 (Lecture)** - (I) Quantifying erosion with thermochronology, (II) Thermochronology for landscape evolution
- Readings: Braun et al., Chapters 1-3

**4.5 (Lab)** - Exercise 7: Predicting thermochronometer ages II
- Homework: Exercise 6 write-up due

### Final project deadline
**13.5 - Final project (includes Exercise 7) due by 17.00**
