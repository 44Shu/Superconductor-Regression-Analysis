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

In this report I will also be referencing Kam Hamidieh's Paper on the same dataset, where he instead used machine learning to model the data. His work also included gathering the data and aggregating it into a great format and making it publicly available on UCI's Machine Learning Repo.

Hamidieh, Kam. “A Data-Driven Statistical Model for Predicting the Critical Temperature of a Superconductor.” Computational Materials Science, vol. 154, 2018, pp. 346–354., doi:10.1016/j.commatsci.2018.07.052.

## Project Structure

In this project:

- The analysis code will be contained in the `rscripts` folder, 
- Any Report markdown and html code will be held in the `reports` folder.
- The project data will be held in in the `raw_data` folder.
- Any plots and figures will also be output to the `plots` or `assets` folder.

This structure allows for working with large datasets and information without the drawbacks of an r-markdown file's memory inefficiency.
