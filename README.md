# Food Delivery Time Analysis

Take Home Test for the Data Analyst & Business Intelligence Bootcamp at Dibimbing.id (DABI 23).

## Background
Slow deliveries hurt customer satisfaction and courier productivity. This project looks at
1,000 food delivery orders to find out which factors make deliveries take longer, and what
the business can do about it.

## Dataset
[Food Delivery Time Prediction](https://www.kaggle.com/datasets/denkuznetz/food-delivery-time-prediction) (Kaggle)
1,000 orders, 9 columns. Target variable: `Delivery_Time_min`.

## Tools
- Python (Google Colab): data cleaning, EDA, statistical tests
- Power BI: interactive dashboard (2 pages)

## Files
| File | Description |
|---|---|
| `THT_Food_Delivery_Analysis.ipynb` | Data preprocessing, EDA, insights, and recommendations |
| `THT_Food_Delivery_Dashboard_Prabaswara.pbix` | Power BI dashboard |
| `Food_Delivery_Times.csv` | Raw dataset |
| `Food_Delivery_Clean.csv` | Cleaned dataset used in Power BI |

## Key Findings
- 41.5% of orders take more than 60 minutes.
- Distance is the strongest factor. 90.8% of orders over 15 km arrive late.
- High traffic adds about 12 minutes compared with low traffic.
- Bad weather combined with high traffic pushes the late rate to 68.5%.
- Time of day and vehicle type have almost no effect on delivery time.

## Author
Prabaswara Trirespati
