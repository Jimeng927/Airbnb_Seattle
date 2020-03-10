# Airbnb_Seattle
# Table of Contents
1. [Installation.](#inst)
2. [Project Motivation.](#motiv)
3. [File Descriptions.](#file)
4. [Results.](#res)
5. [Licensing, Authors, and Acknowledgements.](#ac)

<a name="inst"></a>
## 1. Installation
The packages that I used in the Jupyter Notebook include:

`numpy`

`pandas`

`matplotlib`

`seaborn`

`calendar`

`wordcloud`

`sklearn`

`scipy`

<a name="motiv"></a>
## 2. Project Motivation

For this project, I was using the Airbnb listing data available in Seattle area in year 2016. I was interested in using data analysis and machine learning to understand:

1. How does the listing prices vary over a long and short period of time?
2. What factors contribute most to the price? Location? House sizes?
3. What are guests looking for in an Airbnb list?

<a name="file"></a>
## 3. File Descriptions

There is one `.ipynb` file. The file is used to wrangle data, analyze data and share the results. Markdown cells were used to assist in walking through the thought process for individual steps.

<a name="red"></a>
## 4. Results

There are two parts of the results: **descriptive statistics** and **predictive statistics**. Below are some of the key results from each part:

**descriptive statistics:**

* Listing price distribution

* Listing availability

* Average listing price variation by day, weekday, and month

* Most used words from listing summary and guest reviews

**predictive statistics:**

I used **Random Forest Regression** to predict the listing price with associated features. I then optimized the model and displayed the top 15 features that are used to predict the listing price.

<a name="ac"></a>
## 5. Licensing, Authors, and Acknowledgements

This project is licensed under the MIT License. You can find the original dataset via the Kaggle link [here](https://www.kaggle.com/airbnb/seattle). 
