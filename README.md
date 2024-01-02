# LION Stock Performance Analysis and Prediction

## Overview

Welcome to the LION Stock Performance Analysis and Prediction repository! In this project, we explore and analyze the historical performance of the LION stock. The dataset includes various indicators such as closing prices, trading volume, moving averages, MACD, RSI, ROC, and a binary indicator of whether good returns would have been made within 7 days of buying the stock.

## Dataset Details

- **Close:** The closing value of the stock for a given day.
- **Volume:** The number of shares traded on that day.
- **EMA 5, EMA 13, EMA 26:** Exponential Moving Averages with different periods.
- **MACD:** Moving Average Convergence Divergence indicator.
- **Signal:** The 9-day EMA of the MACD.
- **RSI:** Relative Strength Index used to assess price momentum.
- **ROC:** Rate-of-Change indicator measuring the percent change in price from one period to the next.
- **Worked?:** Binary indicator (1 = Yes, 0 = No) for whether good returns would have been made within 7 days of buying.
- **Percentage Returns:** The maximum returns the stock gave within 7 days of buying.

## Tasks

### Data Exploration and Analysis

Explore the dataset creatively, deriving meaningful insights using visualizations. Identify patterns, trends, and potential seasonality in the stock performance. Use plots to communicate unique aspects of the data to the reader.

### Model Training

1. **Classification Model:**
   - Split the data into training and validation sets.
   - Utilize any classification algorithm of your choice to predict the 'Worked?' column.
   
2. **Regression Model:**
   - Predict the 'Percentage Returns' column using a regression model of your choice.

### Evaluation and Results

Evaluate the models on the validation data using proper metrics. Display the results in a clear and concise manner, providing insights into the model's performance for both classification and regression tasks.

## Repository Structure

- **`data/`:** Directory containing the dataset in CSV format.
- **`notebooks/`:** Jupyter notebooks for data exploration, model training, and evaluation.
- **`results/`:** Folder to store model evaluation results.
- **`src/`:** Source code for data preprocessing, model training, and evaluation.
- **`README.md`:** Main documentation file containing an overview, tasks, and instructions.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/LION_Stock_Prediction.git
   cd LION_Stock_Prediction
