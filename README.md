## Table of Contents
* [Installations](#installations)
* [Project Motivation](#project-motivation)
* [File Descriptions](#file-descriptions)
* [Results](#results)
* [Acknowledgements](#acknowledgements)

## Installations
All of the following packages were used for this project and can be found in the standard Anaconda distribution for Python 3.7:
* Jupyter notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Seaborn

## Project Motivation
As part of Udacity's [Data Scientist Nanodegree](https://www.udacity.com/school-of-data-science) program, I was tasked with selecting a dataset and investigating it using the CRISP-DM process before sharing my results in a blog post and public repository.  I chose to investigate the 2017 Stack Overflow developer survey results and asked the following questions:
1. What developer types overlap with data scientists?
2. What types of education do data scientists recommend?
3. What effect does being a data scientist have on salary?

## File Descriptions
There are three files in this repository: two data files and the Jupyter notebook with my workflow:
* `survey_results_public.csv`: CSV file containing all of the results from the 2017 Stack Overflow developer survey.  This was the source of all of the data for this project.
* `survey_results_schema.csv`: CSV file containing the text of 154 questions asked in the survey, as well as their column name in the 'survey_results_public.csv' file.  This file was useful for understanding what questions were asked in the survey and how to identify them in the dataset.
* `Investigating How Data Scientists Answered the Stack Overflow Survey.ipynb`: Jupyter notebook containing all of my work on this dataset.  This was a working notebook, so it contains all of the data exploration, cleaning, analysis, and results, as well as my thought process throughout the project.

## Results
Please see my blog post here (link) for the main results of my analysis.

## Acknowledgements
This project would not have been possible without Stack Overflow collecting and sharing this data.  I accessed the data through [Kaggle](https://www.kaggle.com/stackoverflow/so-survey-2017).  I also found Stack Overflow posts and the documentation for each of the python packages extremely helpful in completing this project.
