# Customer-Lifetime-Value

This repository contains a comprehensive analysis of Customer Lifetime Value (CLV) using various data science tools and Python libraries. The project employs a combination of Gamma-Gamma and BG/NBD models to predict CLV and subsequently segment customers based on their predicted lifetime value.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Libraries Used](#libraries-used)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer Lifetime Value (CLV) is a crucial metric that helps businesses understand the long-term value of their customers. This project aims to analyze and predict CLV using transaction data and advanced statistical models. By accurately predicting CLV, businesses can tailor their marketing strategies and improve customer retention.

## Data

The data used in this analysis is sourced from the UCI Machine Learning Repository and pertains to online retail transactions. The dataset includes information about transactions related to customer purchases and lifetime value.

- **Dataset Source:** [Online Retail Data Set](https://archive.ics.uci.edu/dataset/352/online+retail)

## Libraries Used

The following Python libraries were utilized in this project:

- `pandas`: Data manipulation and analysis
- `numpy`: Numerical computations
- `matplotlib`: Data visualization
- `sklearn`: Machine learning algorithms
- `lifetimes`: Customer lifetime value modeling
- `datetime`: Handling date and time data

## Methodology

The project follows these steps:

1. **Data Collection:** Acquired the transaction data from the UCI Machine Learning Repository.
2. **Data Preprocessing:** Cleaned and prepared the data for analysis.
3. **Feature Engineering:** Created features necessary for modeling CLV.
4. **Modeling:**
   - Used the **BG/NBD** model to predict the number of transactions.
   - Used the **Gamma-Gamma** model to predict the monetary value of transactions.
5. **Prediction:** Combined the results from both models to predict the Customer Lifetime Value.
6. **Customer Segmentation:** Segmented customers based on their predicted CLV.
7. **Visualization:** Visualized the results using various plots and charts.

## Results

The analysis resulted in accurate predictions of Customer Lifetime Value. Customers were segmented into different groups based on their predicted CLV, allowing for targeted marketing and retention strategies.

## Usage

To reproduce the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ramialnajdi/Customer-Lifetime-Value.git
    cd CLV-Analysis
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook:
    ```bash
    jupyter notebook Customer-Lifetime-Value.ipynb
    ```

