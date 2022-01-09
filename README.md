# Bertelsmann-Arvato
Bertelsmann/Arvato Project - Data Scientist Nanodegree

### Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. How To Run

## Installation<a name="installation"></a>
To run code use python>=3.8, to install dependencies run pip install -r requirements.txt

## Project Motivation<a name="motivation"></a>
The Project focus on finding the potential customers in the general population by analysing already exsting customer records.
Bertelsmann-Arvato has collected and provided following levels of Information for exting customers and the general population.
- Person : gender, age, financial typology,helath typology, social status, etc.
- Household : Number of person in house, structure, household income, consumption type, transaction activity in last 24 months, etc
- Building : Number of household in building, number of acedemic holders, building type, distance from point of sale, etc.
- Microcell (RR4_ID)  : New German CAMEO Typology established together with Call Credit in late 2015
- Microcell (RR3_ID) : share of car owners, number of building in microcell, indicatio whether it is a growing or declining microcell
- 125 x 125m Grid : transactional activity based on product group. 
- Postcode : distance from next metropole, city centre, etc.
- RR1_ID : purchasing power, moving patterns, etc.
- PLZ8 : share of cars wrt engine power, brand, etc.
- Community : share  of unemployed person in community, inhabitants, etc.

## File Description<a name="description"></a>
1. Arvato Project Workbook.ipynb - jupyter notebook exploring different aspects of Bertelsmann-Arvato data. 
2. DIAS Information Levels - Attributes 2017
3. DIAS Attributes - Values 2017

## How To Run<a name="run"></a>
- Prepeare and run virtual environment:\
	- Python -m venv <virtual_env_name>
	- source <virtual_env_name>/bin/activate
	- https://docs.python.org/3/library/venv.html
- Install Dependencies 
	- pip install -r requirements.txt

- open and run jupyter-notebook
	- if you want to run jupyter-notebook in virtual environement refer: https://www.geeksforgeeks.org/using-jupyter-notebook-in-virtual-environment
	- run jupyter-notebook command
	- open Arvato Project Workbook.ipynb
	- Please make sure you have the AZDIAS, CUSTOMERS and MAILOUT DATA present before running notebook.


