# 📈 Stock Market Analysis: Tesla (TSLA)

This project performs a basic but insightful analysis of **Tesla (TSLA) stock data** to understand its historical performance, risk profile, and trading patterns.

---

## 🚀 Project Goal
The main goal is to use fundamental data analysis techniques to explore and visualize key financial metrics for Tesla stock, including:
* Pricing trends and movement over time.
* Daily volatility and risk.
* The relationship between trading volume and stock price.

---

## 🛠️ Technologies Used
This analysis is conducted using a **Jupyter Notebook** (`Stock_Market_Analysis.ipynb`) with the following Python libraries:
* **Pandas & NumPy:** For data handling and calculations.
* **Matplotlib & Seaborn:** For creating all the visualizations and plots.

---

## 📊 Analysis Highlights

### 1. Volume vs. Close Price (Scatter Plot)
* **Result:** There is a **strong, non-linear positive correlation** between the number of shares traded (**Volume**) and the final daily price (**Close Price**).
* **Interpretation:** High trading activity generally drives the stock price higher.

### 2. Distribution of Daily Returns (Histogram)
* **Result:** The plot is **highly peaked around zero** with noticeable data points far out on the edges (fat tails).
* **Interpretation:** The stock is generally stable on a daily basis (most returns are near zero), but it carries a **higher-than-normal risk** of experiencing extreme large gains or losses.

### 3. Price Change Over Time (Line Plot)
* **Result:** The price change shows distinct phases of activity.
* **Interpretation:** The stock experienced **periods of extreme volatility** (large, sharp price swings) at the beginning and the end of the analyzed time period, separated by a long phase of **relative stability and low price movement** in the middle.

---

## ⚙️ How to Run the Project
1.  **Clone the Repository (or download the files).**
2.  **Install Libraries:** Ensure you have Python, Pandas, NumPy, Matplotlib, and Seaborn installed.
3.  **Open the Notebook:** Open the `Stock_Market_Analysis.ipynb` file using Jupyter or Google Colab.
4.  **Run Cells:** Execute all cells in the notebook sequentially to load the data, perform calculations, and generate the plots.

---

## 📁 Files in This Project
* `Stock_Market_Analysis.ipynb`: The main Jupyter Notebook containing all the code and analysis steps.
* *stock_data_tysla.csv:The raw data file containing daily stock prices for TSLA.
