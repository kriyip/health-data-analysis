# health-data-analysis
Final project for Intro to Data Science (STAT 4770/7770).

This project attempts to determine and analyze several predictive variables on a county's poor health index. The investigated explanatory variables are categorized into the following four cateogries: quality of health care, environmental factors, behavioral factors, and demographic/political factors. The relationship between these variables and the poor health index is investigated using exploratory data analysis, predictive regression modeling, and decision trees.

## Structure
This repository consists of three parts:
- `data`: Folder containing the datasets and metadata about those datasets.
- `health-analysis.ipynb`: Jupyter notebook. Contains the Python analysis code.
- `health-analysis.html`: A static HTML version of the Jupyter Notebook. Used for viewing the analysis without needing to run the code.

## Data
The primary data source of this project is https://www.countyhealthrankings.org.
The key variable being analyzed is the `Poor.Health` index, which is a quantified measurement of poor health on the county level. The analysis primarily explored the median household income, uninsurance rate, and excessive drinking/smoking as explanatory variables of a county's poor health index; these variables were selected from a correlation analysis of variables in the dataset and also for largely being solid proxies for socioeconomic status.

For an in-depth overview of the dataset, refer to `data/data_dictionary.pdf`
