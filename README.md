# Passenger Satisfaction Dataset - Data Understanding and Preparation

This project is part of an assignment where we analyze an altered version of the **Passenger Satisfaction** dataset to understand its contents and prepare it for future classification and regression tasks. The dataset is derived from a customer satisfaction survey conducted by **Buckeye Airlines, Inc. (BAI)**, and is intended to identify key factors that affect customer satisfaction.

The project follows the **CRISP-DM process model**, specifically focusing on Steps 2 and 3: **Data Understanding** and **Data Preparation**. The dataset provided contains errors such as duplicate records, missing values, and erroneous data, which have been intentionally introduced for the purpose of this exercise.

## Project Objectives

The main objectives of this project are:
1. To analyze the provided dataset and understand its contents.
2. To identify and fix any issues, preparing a clean dataset that can be used for future model building and analysis.
3. To effectively communicate insights and results from the dataset in a clear and structured manner.

## Dataset Overview

- **Dataset Name**: `satisfaction_teb1_for_post.xlsx`
- **Source**: Adapted from [Kaggle - Customer Satisfaction Dataset](https://www.kaggle.com/datasets/johndddddd/customer-satisfaction)
- **Target Attribute**: `satisfaction_v2` (overall customer satisfaction, which will eventually be predicted in future assignments)
- **Dataset Description**: The dataset contains various attributes representing passenger satisfaction levels with different services provided by Buckeye Airlines, such as seat comfort, inflight service, and entertainment. This dataset has been intentionally altered with data errors for use in this assignment.

## Tasks Performed

### 1. Data Understanding (Exploratory Data Analysis)
   - **Goal**: Understand the structure, contents, and quality of the dataset.
   - **Actions**:
     - Load and inspect the dataset (data types, null values, unique values).
     - Analyze each attribute, understanding its relevance to customer satisfaction.
     - Visualize data distributions and relationships between variables to identify any patterns or inconsistencies.
   - **Results**: Insights into missing values, erroneous entries, and important features that could potentially influence the target attribute.

### 2. Data Preparation
   - **Goal**: Clean and prepare the dataset for future analysis and modeling.
   - **Actions**:
     - Handle missing values (imputation or removal based on the situation).
     - Detect and remove duplicate records.
     - Correct erroneous attribute values.
     - Transform or encode categorical data as necessary for future modeling.
   - **Results**: A clean, pre-processed dataset saved for future use, ready for building classification or regression models.

## Requirements

The following Python libraries were used to perform the analysis:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
