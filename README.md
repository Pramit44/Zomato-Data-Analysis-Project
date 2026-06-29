# Zomato Data Analysis Project

## Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on a real-world Zomato Dataset using Python. The primary objective is to analyze restaurant attributes—such as online/offline booking modes, customer ratings, votes, and average costs—to extract actionable consumer insights and drive data-backed business strategies for food aggregation platforms.

## Key Features & Analysis Performed
* **Data Cleaning & Type Standardization**: Built a custom data-cleaning function to transform string-based ratings (e.g., '4.1/5', '3.8 /5') into continuous float variables while systematically handling missing values and new restaurant flags ('NEW', '-').
* **Consumer Demand & Popularity Mapping**: Analyzed the volume distribution and total customer engagement (votes) across various restaurant types, identifying "Dining" as the heavily dominant segment with over 20,000 votes.
* **Financial Spending Analysis**: Filtered and evaluated online order metrics to establish the baseline average spending for couples (two people) on the platform, which rounds out to approximately ₹510.
* **Rating Dynamics**: Investigated the distribution of maximum ratings across online and offline ordering channels, revealing distinct differences in customer satisfaction benchmarks.
* **Targeted Marketing Segmentation**: Isolated and segmented offline dining data to pinpoint high-traffic restaurant categories, providing Zomato with a data-driven strategy for high-ROI promotional rollouts.

## Technologies & Libraries Used
* **Language**: Python
* **Data Manipulation**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn
* **Environment**: Jupyter Notebook (`Zomato Data Analysis.ipynb`)

## Key Insights Discovered
* **Dine-In Preference**: The "Dining" category significantly outperforms other types in both availability and total audience engagement, representing a major revenue and traffic driver.
* **Ambiance Premium**: Offline orders consistently secure higher peak ratings compared to online deliveries, highlighting that direct service and ambiance substantially uplift customer satisfaction.
* **Promotional Strategy**: Because Dining outlets attract the highest volume of offline walk-ins, they serve as the ideal partners for Zomato's offline discount campaigns.

## How to Run This Project

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/Pramit44/Zomato-Data-Analysis-Project.git](https://github.com/Pramit44/Zomato-Data-Analysis-Project.git)

