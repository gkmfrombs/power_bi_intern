# Dark Store AI: Hyper-Local Demand Forecasting 🛒🤖

## Overview
This repository contains the code and data visualizations for the **Dark Store AI** capstone project. 

In the quick commerce industry (e.g., Blinkit, Zepto), delivering groceries within 10 minutes requires highly localized "dark stores." This project solves the critical business challenge of overstocking perishable goods and preventing stockouts by predicting the exact inventory required at each specific hour of the day.

## Proposed Solution
The system is built in two distinct phases:
1. **Machine Learning Forecasting:** An AI-driven predictive model that calculates future demand based on historical purchase data, day of the week, and hourly traffic spikes.
2. **Business Intelligence Dashboard:** An interactive dashboard that allows store managers to explore peak hours, detect traffic anomalies, and view forecasted inventory needs.

## Tech Stack 🛠️
* **Data Processing & ML:** Python, Pandas, NumPy, Scikit-Learn
* **Algorithm:** XGBoost Regressor (Time-Series Forecasting)
* **Environment:** Google Colab
* **Business Intelligence & Deployment:** Microsoft Power BI, DAX, Power Query

## Project Files
* `dark_store_model.ipynb`: The Google Colab Python notebook containing the data preprocessing, feature engineering, and the XGBoost model training.
* `dark_store_demand.csv`: The combined dataset featuring 30 days of historical data and 7 days of AI-predicted future data.
* `Dark_Store_AI_Dashboard.pbix`: The interactive Power BI dashboard file featuring the forecasting line charts, matrix heatmaps, and AI anomaly detection.
* `MS_Elevate_Presentation.pptx`: The slide deck used for the project presentation.

## How to View the Project
### 1. The Machine Learning Model
You can view the Python code and model training process by opening the `dark_store_model.ipynb` file directly in GitHub or by loading it into Google Colab.

### 2. The Power BI Dashboard
To interact with the final dashboard:
1. Download the `Dark_Store_AI_Dashboard.pbix` file.
2. Open it using Microsoft Power BI Desktop.
3. The dashboard features three interactive pages: Executive Summary, Demand Patterns, and AI Insights.

## Author
**Guddu Kumar Mishra** * Data Science and Applications, IIT Madras
* GitHub: [@gkmfrombs](https://github.com/gkmfrombs)