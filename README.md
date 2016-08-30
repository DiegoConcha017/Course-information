# Introduction to Quantitative Geology <br /> (Course 54070) - Fall 2016

## Course meetings
**Period I: 5.9-20.10** (Together with Automating GIS processes course)
- Mondays 8-10 *and* 10-12, A113-A114, Physicum
- *Work sessions on Thursdays 8-10, A111-112, Physicum*

**Period II: 31.10-12.12**
- Mondays 8-10 *and* 10-12, D211, Physicum
- *Work session dates/times to be determined*

## Instructor
- David Whipp
- Office: D430, Exactum
- Email: `firstname.lastname@helsinki.fi`
- Phone: (0)2 941 51617

## Course assistant
- Jorina Schütt
- Office: D422, Exactum
- Email: `firstname.lastname@helsinki.fi`
- Phone: (0)45 1865288

## Course websites
**Period I**:
- Main course site:  [https://github.com/Python-for-geo-people](https://github.com/Python-for-geo-people)

**Period II**:
- Main course site:
 [https://github.com/Intro-Quantitative-Geology](https://github.com/Intro-Quantitative-Geology)
- Moodle page: [https://moodle.helsinki.fi/course/view.php?id=12453](https://moodle.helsinki.fi/course/view.php?id=12453)

## Textbooks
There are **no required textbooks** for this course. This course uses a wide range of sources for course information and the main textbooks are given below.

Recommended textbooks (in order of relevance):
- Zelle, J. (2010) [Python Programming: An Introduction to Computer Science](http://mcsp.wartburg.edu/zelle/python/ppics2/index.html), Second edition. Franklin, Beedle & Associates.
- Stüwe, K. (2007) [Geodynamics of the Lithosphere](http://wegener.uni-graz.at/publication/books/geodyn2nd/), Second edition. Springer.
- Braun, J., van der Beek, P. and Batt, G. (2006) [Quantitative Thermochronology: Numerical Methods for  the Interpretation of Thermochronological Data](http://www.cambridge.org/us/academic/subjects/earth-and-environmental-science/geochemistry-and-environmental-chemistry/quantitative-thermochronology-numerical-methods-interpretation-thermochronological-data), First edition. Cambridge University Press.
- Taylor, J. R. (1997) [An Introduction to Error Analysis: The Study of Uncertainties in Physical Measurements](http://www.uscibooks.com/taylornb.htm), Second edition. University Science Books.

Optional textbooks:
- Pelletier, J. (2008) [Quantitative Modeling of Earth Surface Processes](http://www.cambridge.org/us/academic/subjects/earth-and-environmental-science/geomorphology-and-physical-geography/quantitative-modeling-earth-surface-processes?format=HB), First edition. Springer.
- Trauth, M. H. (2010) [MATLAB® Recipes for Earth Sciences](http://www.springer.com/cn/book/9783642447167), Third edition. Springer.
- Beazley, D. M. (2012) [Python Essential Reference](http://www.dabeaz.com/per.html), Fourth edition. Addison-Wesley.

## General description of the course
This course aims to:

1. Introduce students to the Python programming language and its application to modelling Earth science data/processes
2. Develop basic programming skills through analysis of fundamental equations used in the Earth sciences
3. Present some established techniques for comparing geologic data to numerical model predictions

## Course format
The majority of this course will be spent in front of a computer learning to program in the Python language and working on numerical modelling exercises about geological processes and data.
I would like to note, though, that the course format has changed in several ways from years past.

1. This year we will meet exclusively in computer classrooms to work on exercises and the only a small amount of classroom time will be given to proper lectures.
In the past, half of the course was lecture time and half was in a computer classroom.
2. To compensate for the lack of lectures, short video lectures will be provided online in advance of *some* exercises. These lectures should be viewed prior to coming to class and will give you the necessary background to complete the computer exercises. They can also be rewatched as often as needed :).
3. During Teaching Period I, we will be meeting together with the Automating GIS processes course and focus on learning to program in Python. Previously, both this course and the Automating GIS processes course lacked sufficient time for students to properly learn the basic concepts of programming in Python. We hope this extended time learning Python will be helpful later in the course (i.e., in Period II) when we work on the geological applications.

Due to these changes, the course format will be an experiment this year, but it is one that I think will benefit all of us.

The computer exercises will focus on developing basic programming skills using the Python language and applying those skills to topics from the video lecture material. Typical exercises will involve a brief introduction followed by topical computer-based tasks. At the end of the exercises, you may be asked to submit answers to relevant questions, some related plots, and/or Python codes you have written or used. You are encouraged to discuss and work together with other students on the laboratory exercises, however the laboratory summary write-ups that you submit must be completed individually and must clearly reflect your own work.

## Grading
Course grades will be given using the standard six-level grading scale from 0 to 5. Your grade will be based on (1) weekly laboratory exercise summary write-ups, and (2) a course project (briefly described below). The weight of each item is given below.
- 50% - Exercise write-ups (14 in total)
- 50% - Final project report

Note: Deadlines for exercise write-ups and the term project are **firm** and given in the schedule on the following pages. Exercise write-ups will be due by the start of lab on the due date. If you anticipate you will not be able to submit any of these items by the given deadline, you should let me know as early as possible and must let me know at least one day in advance. Late write-ups will be marked down 25\% per day late, so please submit it on time.

## Final project
The final project is based on the results you will produce in the final two exercises. In these exercises, you will modify a Python code to read in a data file, make some basic calculations using some of the equations we’ve discussed earlier in the course and produce a series of plots. The goal of the exercise is to model a geological dataset and use your model to interpret the data. The final project report will involve writing a short paper with the introductory and background material for the data from the final two exercises, presenting your results in a series of plots with a short section of text, and discussing the meaning of the results. The intent is for you to write a short scientific paper with the same content that would typically be present in a scientific journal article. Details on the final project paper will be given later in the course.

## Course topics by week
*Lecture content, readings and due dates are subject to change*
### Basic concepts of quantitative geology
**14.3 (Lecture)** - (I) [What is Quantitative Geology?](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/01-What-is-quantitative-geology/01-What-is-quantitative-geology.pdf), (II) [Essentials of computing](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/02-Essentials-of-computing/02-Essentials-of-computing.pdf)
- Readings: Stüwe, Chapter 1; Zelle, Chapters 1 & 2

**16.3 (Lab)** - [Exercise 1: Introduction to Python and NumPy I](https://github.com/Intro-Quantitative-Geology/Python-and-NumPy-I)
- Homework: None

### Dealing with age data: Radioactivity and essential geostatistics
**21.3 (Lecture)** - (I) [Common statistical methods in geoscience](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/03-Common-statistical-methods-in-geoscience/03-Common-statisical-methods-in-geoscience.pdf), (II) [What do geochronologic ages mean?](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/04-What-do-geochronological-ages-mean/04-What-do-geochronological-ages-mean.pdf)
- Readings: Taylor, Chapters 2 & 4

**23.3 (Lab)** - [Exercise 2: Introduction to Python and NumPy II](https://github.com/Intro-Quantitative-Geology/Python-and-NumPy-II)
- Homework: Exercise 1 write-up due

### 28.3, 30.3 - NO CLASS (Easter holiday break)

### Hillslope sediment transport and heat transfer: The diffusion equation 
**4.4 (Lecture)** - (I) [Natural diffusion: Hillslope sediment transport, Earth’s thermal field](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/05-Natural-diffusion/05-Natural-diffusion.pdf), (II) [Solving the diffusion equation](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/06-Solving-the-diffusion-equation/06-Solving-the-diffusion-equation.pdf)
- Readings: Stüwe, Chapter 3; Pelletier, Chapter 2

**6.4 (Lab)** - [Exercise 3: Uplift and diffusion of the Earth’s surface](https://github.com/Intro-Quantitative-Geology/Hillslope-diffusion)
- Homework: Exercise 2 write-up due

### Fluvial incision and rock uplift: The advection/wave equation
**11.4 (Lecture)** - (I) [Advection of the Earth’s surface: Fluvial incision and rock uplift](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/07-Advection-of-the-Earths-surface/07-Advection-of-the-Earths-surface.pdf), (II) [Solving the advection/wave equation](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/08-Solving-the-advection-equation/08-Solving-the-advection-equation.pdf)
- Readings: Stüwe, Chapter 3; Pelletier, Chapter 4

**13.4 (Lab)** - [Exercise 4: River profile calculations](https://github.com/Intro-Quantitative-Geology/River-advection)
- Homework: Exercise 3 write-up due

### Viscous flow of rock and ice: (Non-)Newtonian flow equations
**18.4 (Lecture)** - (I) [Rocks and ice as viscous materials](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/09-Rock-and-ice-as-viscous-materials/09-Rock-and-ice-as-viscous-materials.pdf), (II) [Equations of viscous flow](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/10-Viscous-flow-down-an-incline/10-Viscous-flow-down-an-incline.pdf)
- Readings: Stüwe, Chapter 5; Pelletier, Chapter 6

**20.4 (Lab)** - [Exercise 5: Glacier mechanics](https://github.com/Intro-Quantitative-Geology/Lab-exercise-5)
- Homework: Exercise 4 write-up due

### Quantitative thermochronology: Linking ages to processes
**25.4 (Lecture)** - (I) [Basic concepts in thermochronology](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/11-Basic-concepts-of-thermochronology/11-Basic-concepts-of-thermochronology.pdf), (II) [Low-temperature thermochronology](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/12-Low-temperature-thermochronology/12-Low-temperature-thermochronology.pdf)
- Readings: Braun et al., Chapters 1-3

**27.4 (Lab)** - [Exercise 6: Predicting thermochronometer ages I](https://github.com/Intro-Quantitative-Geology/Lab-exercise-6)
- Homework: Exercise 5 write-up due

**2.5 (Lecture)** - (I) [Quantifying erosion with thermochronology](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/13-Quantifying-erosion-with-thermochronology/13-Quantifying-erosion-with-thermochronology.pdf)
- Readings: Braun et al., Chapters 1-3

**4.5 (Lab)** - [Exercise 7: Predicting thermochronometer ages II](https://github.com/Intro-Quantitative-Geology/Lab-exercise-7)
- Homework: Exercise 6 write-up due

### Final project deadline
**13.5 - [Final project](https://github.com/Intro-Quantitative-Geology/Thermochronology-I/blob/master/Final-report.md) (includes Exercise 7) due by 17.00**
