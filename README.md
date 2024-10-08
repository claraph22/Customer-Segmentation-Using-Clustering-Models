
# Telecommunication Customer Churn Analysis
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Portfolio Project](https://img.shields.io/badge/portfolio-project-important)

This project aims to analyze customer churn for a telecommunication company. Using a dataset sourced from Kaggle, the objective is to explore customer behavior patterns and identify the factors that lead to churn.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)


## Introduction

Customer churn refers to the situation where customers stop using a company's services. In this project, we aim to understand the factors associated with churn and how the company can reduce it. The dataset used comes from a telecom company and contains information about customers such as their services, account information, and demographic data.

**Author:** Clara Putri Herlin  

## Dataset

The dataset used in this project can be found on Kaggle:  
[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

The dataset includes the following columns:
- Customer information: `customerID`, `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- Services subscribed: `PhoneService`, `InternetService`, `Contract`, etc.
- Customer account information: `tenure`, `MonthlyCharges`, `TotalCharges`
- Target variable: `Churn`

## Installation

To run the analysis in this notebook, you need to install the following:

- Python 3.8 or higher
- Jupyter Notebook
- Common Python libraries such as:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

You can install these dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

To run the notebook, simply open it in Jupyter and execute the cells. The notebook contains all the necessary code to load the dataset, preprocess the data, and perform exploratory data analysis (EDA) and model training.

```bash
jupyter notebook P1M2_Clara.ipynb
```

## Project Structure

- `P1M2_Clara.ipynb`: The main Jupyter notebook containing the code and analysis.
- `README.md`: This file, providing an overview of the project.

## Results

This project analyzes the dataset to identify factors contributing to customer churn. Several machine learning models are tested to predict churn, and the performance of these models is evaluated using appropriate metrics such as accuracy, precision, and recall.
