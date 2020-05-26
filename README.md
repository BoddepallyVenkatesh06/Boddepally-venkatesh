Write a Data Science blog post
Udacity Data Scientist Nanodegree Project.

Table of Contents
Installation
Project Motivation
File Description
Results
Licensing, Authors, and Acknowledgements
Installation
This code runs with Python version 3.* and requires some libraries, to install theses libraries you will need to execute:
pip install -r requirements.txt

You will need to download Stackoverflow’s 2017 and 2018 Annual Developer Survey and put in specific folders. You can find the data to download here.

To move the downloaded files to the specific folder, you can execute.

Stackoverflow’s 2017 data
mv survey_results_public.csv Write-a-Data-Science-Blog-Post/data/2017/survey_results_public.csv

Stackoverflow’s 2018 data
mv survey_results_public.csv Write-a-Data-Science-Blog-Post/data/2018/survey_results_public.csv

Project Motivation
This is an Udacity Nanodegree project.I was interested in using Stackoverflow Developer Survey Data to better understand:

What are the most used programming languages in Brazil?
What are the most wanted programming languages in Brazil?
How does programming languages used at work relates with programming languages people want to learn?
File Description
exploratory_analysis.ipynb: Notebook containing the data analysis.
data/2017/survey_results_public.csv: Stackoverflow's 2017 Annual Developer Survey data.
data/2018/survey_results_public.csv: Stackoverflow's 2018 Annual Developer Survey data.

Results
The main findings of the code can be found at the post available here

Licensing, Authors, Acknowledgements
Must give credit to Stackoverflow for the data. You can find the Licensing for the data and other descriptive information at the Stackoverflow link available here.
