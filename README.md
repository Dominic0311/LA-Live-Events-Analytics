# LA-Live-Events-Analytics
Dual-purpose SQL, Power BI, and Python analytics pipeline predicting concert revenue and venue attendance.

# LA Live Events Analytics & Revenue Prediction

An end-to-end data analytics project built to evaluate live music tour performance across venues and predict venue revenue.

## Tech Stack
- **Database / ETL:** SQL (SQLite / Google Colab)
- **Business Intelligence:** Power BI (DAX, Star Schema Data Modeling)
- **Predictive Analytics:** Python (scikit-learn, Pandas)

## Project Workflow
1. **SQL Data Cleaning:** Extracted raw tour data, cleaned string formatting (`$`, `/`, `N/A`), and engineered numeric fields for `Tickets_Sold` and `Tickets_Available`.
2. **Power BI Dashboard:** Created dynamic DAX measures (`Total Revenue`, `Total Tickets Sold`, `Sell-Out Rate`) and built an interactive venue performance report.
3. **Machine Learning Model:** Trained a Linear Regression model in Python to forecast concert revenue based on ticket volume and capacity.
