# Avocados Study for USA

EXECUTIVE SUMMARY

Aims and Objectives

The aim of this study is to provide some information for a small company importing avocados into USA. They are aleady importing conventional avocados to some cities on the west and are considering expanding their business to other regions and to include organic avocados to their offered products

Dataset

The data selected for this project comes from Hass Avocado Board in 2018 originally although It was downloaded from https://www.kaggle.com/neuromusic/avocado-prices

Acknowledgements:

Many thanks to the Hass Avocado Board for sharing this data!!

http://www.hassavocadoboard.com/retail/volume-and-price-data


Deliverables

A Jupyter Notebook containing well-formatted, professional looking markdown cells explaining any substantial code. All functions have docstrings that act as professional-quality documentation. The notebook is written to technical audiences with a way to both understand the approach and reproduce the results. The target audience for this deliverable is other data scientists looking to validate your findings. The notebook should be well organized, easy to follow, and code is commented where appropriate. Finally, notebook should clearly show how the results were achieved for each hypothesis test, including how the p-values were calculated.
A user focused README.md file that explains the process, methodology and findings, and clearly showing both technical expertise and ability to communicate the results.
PowerPoint/Google Slide presentation that explains the hypothesis testing, findings, and their relevance to the company/stakeholders. Contain between 5-10 professional quality slides detailing: (a) A high-level overview of your methodology; (b) The results of your hypothesis tests; (3) Any real-world recommendations it can be made based on the findings.

Introduction

The company has no experience on selling organic avocados and they would like a study regarding organic avocado prices and regional differences on those prices .

Hypotheses

H1 – There is a difference on average price of organic avocados and conventional avocados
H0 – There are no difference on average price between organic and conventional avocados

H2- There are regional differences in average prices of avocados

H0 – There are regional differences in average prices of avocados



Methodology

The initial data set was inspected check for invalid or missing data. A column (Unnamed 0:) was drop due to content irrelavant to study. Some relevant columns in the dataset:

Date - The date of the observation
AveragePrice - the average price of a single avocado
type - conventional or organic
year - the year
Region - the city or region of the observation
Total Volume - Total number of avocados sold
4046 - Total number of avocados with PLU 4046 sold ( Hass – small)
4225 - Total number of avocados with PLU 4225 sold (Hass – large)
4770 - Total number of avocados with PLU 4770 sold (Extra Large)

After inspecting the region column is was noted that included some values as 'Northeast' 'SouthCentral' 'Southeast' 'TotalUS' 'West'. 



Findings



Conclusion

