# Sales Department Project

## 📌 Overview
This project focuses on analyzing sales data to uncover insights that can enhance sales strategies and performance.

## 📂 Project Structure

```
├── Sales_Department_Png/             # Visualizations generated during analysis
├── store.csv                         # Dataset containing store information
├── train.csv                         # Dataset containing sales transaction records
├── Sales_Department_Project.ipynb    # Jupyter Notebook with analysis and findings
├── README.md                         # Project documentation
```

## 📊 Datase

The project utilizes two primary datases:

1. **store.csv**: Contains information about different stores, including:
   - **Store ID**: Unique identifier for each store.
   - **Type**: Categorical variable indicating the type of store.
   - **Size**: The physical size of the store.

2. **train.csv**: Includes historical sales data with features such as:
   - **Store ID**: Reference to the store.
   - **Date**: The date of the sales recod.
   - **Weekly Sales**: Sales figures for the given week.
   - **Holiday Flag**: Indicator of whether the week includes a holiday.
   - **Temperature**: Average temperature for the week.
   - **Fuel Price**: Cost of fuel during the week.
   - **CPI**: Consumer Price Index.
   - **Unemployment**: Unemployment rate during the week.

## 🚀 Installation

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/ranjansinghds/Sales-Department-Project.git
cd Sales-Department-Project
```

### 2️⃣ Install dependencies:

Ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🔍 Methodology

### 1. **Data Preprocessing**

- **Handling Missing Value**: Identified and addressed any missing data in the dataets.
- **Feature Engineering**: Created new features to better capture temporal patterns, such as extracting month and year from the `Date` field.
- **Data Mergin**: Combined `store.csv` and `train.csv` datasets based on `Store ID` to consolidate information.

### 2. **Exploratory Data Analysis (EDA)**

- **Sales Trends Analysis**: Examined sales patterns over time to identify seasonal effects and trends.
- **Impact of Holiday**: Analyzed how holidays influence weekly sales figures.
- **Correlation Analysis**: Explored relationships between sales and external factors like `Temperature`, `Fuel Price`, `CPI`, and `Unemploymnt`.

### 3. **Predictive Modeling**

- **Sales Forecasting**: Developed regression models to predict future sales based on historical data and external variales.
- **Model Evaluation**: Assessed model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RSE).

## 📊 Visualizations

Here are some visualizations from the project:

![alt text](https://github.com/ranjansinghds/Sales-Department-Project/blob/main/Sales%20Department%20Project%20Png/Groupby%20month%20customers.png)
![alt text](https://github.com/ranjansinghds/Sales-Department-Project/blob/main/Sales%20Department%20Project%20Png/Groupby%20month%20sales.png)
![alt text](https://github.com/ranjansinghds/Sales-Department-Project/blob/main/Sales%20Department%20Project%20Png/Heatmap.png)
![alt text](https://github.com/ranjansinghds/Sales-Department-Project/blob/main/Sales%20Department%20Project%20Png/Sales%20tarin%20df%20hist.png)
![alt text](https://github.com/ranjansinghds/Sales-Department-Project/blob/main/Sales%20Department%20Project%20Png/sales_predictions.png)
![alt text](https://github.com/ranjansinghds/Sales-Department-Project/blob/main/Sales%20Department%20Project%20Png/sales_train_all_df.pivot_table.png)

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## 📌 Future Improvements

- **Advanced Time Series Models**: Implement models like ARIMA or Prophet for more accurate sales forecasting.
- **Incorporate Additional Data**: Integrate external data sources such as economic indicators or competitor pricing to enhance model perfrmance.
- **Interactive Dashbords**: Develop dashboards using tools like Tableau or Power BI for real-time sales monitoring and decision upport.