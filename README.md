# Trader Performance vs Bitcoin Market Sentiment

## Data Science / Analytics Internship Assignment – Primetrade.ai

This repository contains my submission for the **Round-0 Data Science / Analytics Internship Assignment** at **Primetrade.ai**.

## Project Objective

The objective of this assignment is to analyze the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader behavior on the Hyperliquid platform.

The analysis focuses on identifying whether market sentiment influences:

- Trader profitability
- Trading activity
- Buy/Sell behavior
- Win rate
- Trade size

The findings are used to derive actionable trading insights supported by data.

---

## Tools Used

- Microsoft Excel
- Power Query
- Pivot Tables
- Excel Charts

---

## Workflow

The project was completed using the following workflow:

1. Imported both CSV datasets into Power Query.
2. Cleaned and transformed the datasets.
3. Converted Unix timestamps into Date format.
4. Merged the datasets using a Left Outer Join on the Date field.
5. Removed unmatched records with missing market sentiment.
6. Created analytical metrics using Pivot Tables.
7. Built charts to visualize trader performance and market behavior.
8. Generated business insights and strategy recommendations.

---

## Metrics Analyzed

- Total Closed PnL
- Average Closed PnL
- Trade Count
- Win Rate
- Average Trade Size (USD)
- Buy vs Sell Ratio
- Trading Activity by Market Sentiment

---

## Repository Contents

📄 **Dashboard.xlsx**
- Interactive Excel dashboard containing Pivot Tables, charts, and analysis.

📄 **Cleaned_Trader_Sentiment_Data.csv**
- Cleaned dataset prepared after data transformation and merging.

🖼️ **Pivot_Tables.png**
- Screenshot containing the Pivot Tables used in the analysis.

📄 **Report.pdf**
- Detailed report covering methodology, findings, business insights, recommendations, and limitations.

---

## Key Highlights

- Performed end-to-end data cleaning and preparation using Power Query.
- Merged trader data with Bitcoin Fear & Greed Index.
- Analyzed trader performance across different market sentiment categories.
- Developed Pivot Table-based performance metrics.
- Created business-focused visualizations and recommendations.

---

## Project Limitations

- The Fear & Greed dataset ended before the trader dataset, resulting in unmatched records being removed during data preparation.
- The merged dataset contained only **Extreme Greed**, **Greed**, and **Neutral** sentiment categories.
- The provided dataset did not contain leverage information; therefore, leverage analysis was not performed.
- The analysis is descriptive and based entirely on Microsoft Excel without predictive modeling.

---

## Assignment Information

This project was completed as part of the **Primetrade.ai Data Science / Analytics Internship Selection Process**.

The analysis has been performed solely for educational and evaluation purposes.

---

## Author

**Samkit Jain**



---

⭐ Thank you for visiting this repository.
