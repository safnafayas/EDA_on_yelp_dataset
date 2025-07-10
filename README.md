# EDA on Yelp Dataset

This repository contains an exploratory data analysis (EDA) of the Yelp Business Dataset, focused on understanding business-level characteristics such as reviews, check-ins, ratings, and parking availability. The cleaned dataset can be used for downstream tasks like modeling or insights generation.

## Project Overview

The main objectives of this project are:

* To explore Yelp business data to identify patterns and trends.
* To clean and prepare the dataset for analysis or modeling.
* To investigate features such as business ratings, reviews, parking availability, and credit card acceptance.

## Dataset Summary

* **Original size**: 150,346 rows × 14 columns
* **Features analyzed**:

  * Business name
  * Star ratings
  * Review count
  * Total check-ins
  * Business accepts credit cards
  * Parking options: garage, lot, street, valet
  * Open status
  * Validation status

A sample of the cleaned data is available as `dataset_with_target.csv`.

## File Descriptions

* **Yelp\_Dataset\_EDA.ipynb**: Main Jupyter notebook containing the full EDA pipeline. Executed using Google Colab.
* **README.md**: Project documentation (this file).

## Key Insights

* Businesses with parking tend to have higher check-ins.
* Many entries contain missing values in features like parking, which are handled appropriately.
* Boolean features were standardized to enable downstream use in machine learning tasks.

## Tools & Technologies

* Python
* Google Colab
* pandas, numpy, matplotlib, seaborn

## How to Use

1. Clone this repository:
   `git clone https://github.com/safnafayas/EDA_on_yelp_dataset.git`
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run all cells to generate the cleaned dataset and visual insights.

## Future Enhancements

* Model business success based on features like parking or credit card acceptance.
* Build classification or recommendation systems using the cleaned data.
* Dashboard integration (e.g., Power BI or Plotly Dash).

## Author

Safna Fayas
[GitHub Profile](https://github.com/safnafayas)

