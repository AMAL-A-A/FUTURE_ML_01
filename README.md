# Sales & Demand Forecasting using Machine Learning

## Project Overview
This project focuses on forecasting sales using historical Superstore sales data. A Random Forest Regressor model is used to analyze past sales patterns and predict future sales, helping businesses make informed decisions related to inventory management and demand planning. The project also includes an interactive Power BI dashboard for visualizing sales trends and business insights.


## Dataset
**Dataset:** Superstore Sales Dataset

The dataset contains information such as:
* Order Date
* Sales
* Profit
* Category
* Sub-Category
* Region
* Quantity
* Discount
* Customer Segment
* Ship Mode


## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* Power BI
* Git & GitHub


## Machine Learning Model
* Random Forest Regressor
The model is performs:
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Sales Prediction
- Model Evaluation
- Future Sales Forecasting


## Model Evaluation
The model performance is evaluated using:
* Mean Absolute Error (MAE)
* Root Mean Square Error (RMSE)
* R² Score


## Visualizations
### Python Visualizations
* Sales Trend Over Time
* Monthly Sales Analysis
* Sales by Category
* Sales by Region
* Profit vs Sales
* Actual vs Predicted Sales
* Error Distribution
* Feature Importance
* Historical Sales with 30-Day Forecast

### Power BI Dashboard
The Power BI dashboard provides interactive business insights through two report pages.

### Page 1 – Machine Learning Dashboard
- Total Sales
- Total Profit
- Actual Sales
- Predicted Sales
- Customer Count
- Feature Importance
- Quantity Sold by Region
- Quantity Sold by Category
- Actual vs Predicted Sales
- Monthly Sales Trend

### Page 2 – Business Analytics Dashboard
- States with Profit Greater than 5000
- Most Frequent Shoppers
- Preferred Shipment Mode by State
- Quantity of Products Sold per Year
- Top Selling Products
- Cities with Highest Sales


## Project Structure
```
FUTURE_ML_01
│
├── images/
├── Future_ML_01_PowerBI.pbix
├── Sales_Forecasting.ipynb
├── sales_data.csv
├── transformed_sales_data.csv
├── predictions.csv
├── future_forecast.csv
├── feature_importance.csv
├── requirements.txt
└── README.md
```


## How to Run the Project
1. Clone this repository.
2. Install the required Python libraries:

```
pip install -r requirements.txt
```

3. Open `Sales_Forecasting.ipynb` in Jupyter Notebook or VS Code.
4. Run all notebook cells.
5. Open `Future_ML_01_PowerBI.pbix` using Power BI Desktop to explore the interactive dashboard.


## Business Insights
* Sales vary significantly across different regions.
* Discounts influence both sales and profitability.
* Office Supplies show consistent sales performance.
* Historical sales data can be used to forecast future demand.
* Sales forecasting supports better inventory planning and business decision-making.


## Dashboard Preview
The `images` folder contains screenshots of the generated visualizations and the Power BI dashboard.


## Author
**Amal Abdul Azeez**
