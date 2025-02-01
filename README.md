# ⚽ Football Player Data Analytics 📊  

![Football Analytics](https://your-image-link-here)  

## 📌 Overview  
Football is a **data-driven sport**, and insights from player performance, fitness levels, and game statistics can **revolutionize** team strategies. This project leverages **data analytics and visualization** to analyze **football players' performance metrics**, helping coaches, scouts, and analysts make **data-backed decisions**.  


## 📊 Power BI Interactive Dashboard

[![View Dashboard](https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=for-the-badge&logo=power-bi)](https://app.powerbi.com/view?r=eyJrIjoiMWEzYjY1MzMtODI3YS00MWExLWE3MWQtOGY1YjBkZjI4MTY1IiwidCI6ImI5NDFiMTA2LTE1Y2UtNDQ0MS1hZjIwLTkyODU2M2Y1ZWRkOCJ9)

If the above button does not work, click here: [Power BI Webview](YOUR_POWER_BI_EMBED_LINK_HERE).

The goal of this project is to create meaningful visualizations for football player analytics, including:

- Player performance metrics: Attacking, Defending, Fielding, Goalkeeping, and Overall Scores.
- Economic information: Player value, wage, release clause.
- Data transformation and segregation into different categories for better analysis.
  
This project includes:
1. Data extraction from the FIFA Index dataset.
2. Data transformation and cleaning in Python (Jupyter Notebook).
3. DAX measures and relationships set up in Power BI to visualize the data.
4. Scoring system for various player attributes.

## 🚀 Features  
- **Scoring System:**
    
    - **Attacking Score**: Calculated based on attributes such as finishing, shot power, dribbling, ball control, etc.
    - **Defending Score**: Based on attributes like interceptions, marking, tackling, strength, and aggression.
    - **Goalkeeping Score**: Derived from goalkeeping-related attributes like diving, handling, reflexes, and positioning.
    - **Overall Value**: Based on player value, wage, and release clause.
    
- **Player Segregation:**
    - Data is categorized into attacking, midfield, defending, goalkeeping, and economic categories for clearer analysis.
  
- **Dynamic Visualization**: Use Power BI to visualize key player metrics such as goal-scoring abilities, defensive capabilities, and economic statistics.

## Technologies Used

- **Python**:
    - Pandas for data cleaning and transformation.
    - Jupyter Notebook for coding and data processing.
  
- **Power BI**:
    - Data visualization using tables, charts, and measures.
    - DAX for custom calculations.


## Steps Taken

1. **Data Extraction and Cleaning:**
    - Extracted football player statistics from the [FIFA Index website](https://www.fifaindex.com/).
    - Loaded the dataset into Jupyter Notebook for data cleaning.
    - Trimed unnecessary columns and kept only relevant data for analysis.
    - Renamed columns for clarity.
    - Filtered the dataset for relevant years and player IDs.

2. **Data Transformation:**
    - Created custom formulas for calculating player scores (attacking, defending, fielding, goalkeeping).
    - Segregated data into different categories like `attacking`, `midfield`, `defending`, `goalkeeping`, and `economic`.
    - Implemented a final trimming process to filter data based on player IDs from FIFA 2024 dataset.

3. **Power BI Visualization:**
    - Loaded the cleaned dataset into Power BI.
    - Established relationships between tables using player IDs as the primary key.
    - Created DAX measures to calculate:
        - Attacking Score
        - Defending Score
        - Fielding Score
        - Goalkeeping Score
        - Overall Value (Economic Score)

4. **Final Output:**
    - The final dataset was cleaned, transformed, and saved for visualization.
    - Created interactive Power BI reports to analyze football players' performance based on different metrics.

## 🚀 Features  
✔️ **Player Performance Analysis** – Tracks goals, assists, passing accuracy, and other key metrics  
✔️ **Fitness & Stamina Insights** – Predicts player fatigue based on match data  
✔️ **Comparative Analysis** – Compare players across different leagues and seasons  
✔️ **Predictive Modeling** – AI-powered insights on potential player performance  
✔️ **Visual Analytics Dashboard** – Interactive **Power BI & Matplotlib** visualizations  

## 🏗️ Tech Stack  
- **Programming:** Python (**pandas, numpy, seaborn, matplotlib**)  
- **Machine Learning:** Scikit-Learn for predictive analytics  
- **Data Visualization:** Power BI, Matplotlib, Seaborn  
- **Storage:** CSV datasets, SQL (for structured storage)  
- **Deployment:** Streamlit (for interactive dashboard), Jupyter Notebook  

## 📊 Dataset Used  
The dataset includes:  
📌 **Player Stats:** Goals, assists, shot accuracy, passing %, etc.  
📌 **Match Performance:** Distance covered, sprint speed, stamina loss  
📌 **Injury & Fitness Data:** Recovery rate, fatigue prediction  

## 🔍 Usefulness of the Project  
✅ **For Coaches:** Identify strengths & weaknesses of players  
✅ **For Analysts:** Perform in-depth **data-driven scouting**  
✅ **For Fans:** Understand performance trends and predictions  
✅ **For Sports Scientists:** Monitor player fitness and injury risks  

## 🛠️ Installation & Usage  
1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/yourusername/football-player-analytics.git  
cd football-player-analytics  
