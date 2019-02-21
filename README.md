# Project Details

* Author: Eduardo Escoto
* Instructor: Professor Jiyoun Myung
* TA: Alex Bernstein | Section: Friday, 10 AM
* Perm Number: 7611817
* e-mail: e_escoto@ucsb.edu

In this project I will be analyzing data gathered from more than 20,000 conductors to see if we can predict a superconductor's critical temperature using regression. We will be focusing on predictors like atomic density, mass, conductivity and the levels of different elements in its composition.

## About the Data

A description of the data set from UCI's machine learning repository can be found below:

> There are two files: (1) train.csv contains 81 features extracted from 21263 superconductors along with the critical temperature in the 82nd column, (2) unique_m.csv contains the chemical formula broken up for all the 21263 superconductors from the train.csv file. The last two columns have the critical temperature and chemical formula. The original data comes from [Web Link] which is public. The goal here is to predict the critical temperature based on the features extracted.

The dataset can also be accessed here at [UCI's Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Superconductivty+Data).

## Project Structure

In this project the analysis code will be contained in the `Analysis_Code.R` file, where the report markdown code will be held in `Analysis_Report.Rmd`. This is due to R markdown files getting unwieldy quickly. No analysis code will be shown in the report unless necessary, and the report will aim to explore my results, techniques, and final conclusions. 