# ecommerce-eda-project
Sales analysis project using Python for an online store. Includes data cleansing, analysis, and visualization.

# Exploratory Data Analysis (EDA) of Online Store Sales

## 🎯 Project Objective

This project performs exploratory data analysis on a dataset from a UK online store. The main objective is to discover purchasing patterns, identify best-selling products, and segment the most valuable customers to inform future business decisions and marketing strategies.

## ❓ Business Questions Analyzed

1. What is the sales trend over time?
2. What days of the week and at what times do sales peak?
3. What are the 10 best-selling products?
4. Who are the 10 most valuable customers (who spend the most)?
5. From which countries are most purchases made?

## 📊 Dataset

The **"Online Retail II UCI"** dataset was used, which contains transactions from an online store between 2009 and 2011. The dataset is available on Kaggle: [Online Retail II UCI](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci).

## 🛠️ Technologies Used

- **Python**: Primary language for analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib and Seaborn**: For creating visualizations.
- **Jupyter Notebook**: As a working environment for presenting the analysis.

## 🚀 Key Findings

- Sales show strong seasonality, with a significant peak in **November**, likely due to pre-Christmas shopping.
- Weekdays, especially Thursdays, are the busiest days for sales, with midday hours (12:00 to 14:00) being the busiest.
- The `WORLD OF WARCRAFT` product is the best-selling product, indicating a specific niche market.
- A small group of VIP customers is responsible for a significant portion of total revenue, highlighting the importance of loyalty strategies.

## 📁 How to use this repository

1. Clone the repository: `git clone https://github.com/YOUR_USER/REPO_NAME.git`
2. Create a virtual environment and install dependencies: `pip install -r requirements.txt`
3. Download the dataset from Kaggle and place it in a folder named `data`.
4. Run the Jupyter Notebook `analisis_ventas.ipynb` to see the full analysis.
