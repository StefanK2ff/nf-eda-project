# neue fische exploratory data analysis project

This project ist my first project of the neue fische data science bootcamp.

The notebooks in this repo can just be executed, if the uses knows the access to the neue fische postgresql data base. From there the inital data is pulled and used as a basis for the analysis.

## Background, goal and tasks

Given was a SQL Database containing information about houses and sales of this houses for the King County district in the state of Washington, US. For a  client which specific needs we should build hypothesis, insights and derivate recommendations.

The scope of the project contains:
1. Creating a structured repo with documentation
2. Conducting the EDA on the given data set in jupyter notebooks
3. Present the results

## Repo structure

The repository contains the following

* [Jupyter notebook to fetch the data from the db](0_Fetching_data.ipynb)
* [Jupyter notebook for basic data understanding and hypothesis building](1_Basic_understanding+Hypothesis.ipynb)
* [Jupyter notebook containing further data exploration](2_Further_data_exploration.ipynb)
* [Jupyter notebook to clean the data](3_Data_cleaning.ipynb)
* [Jupyter notebook to further improve the data for further analysis](4_Data_improvement.ipynb)
* [Jupyter notebook to test the hypothesis](5_Hypothesis_checking.ipynb)
* [Presentation (PDF) of the result](9_Presentation.pdf)

## Requirements

- pyenv
- python==3.11.3


### Environment

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```