# 🎮 Video Game Sales Analysis: What Makes a Blockbuster?

## Overview
An end-to-end data science project analyzing 64,016 video game titles 
to discover what factors make a game commercially successful, 
and using Machine Learning to predict whether a game will be a hit.

## Key Questions
- What makes a video game a blockbuster?
- Which genres, consoles and publishers dominate sales?
- Can we predict a game's success before it releases?
- Will GTA VI be a hit?

## Dataset
- **Source:** Maven Analytics
- **Size:** 64,016 video game titles (1971–2024)
- **Features:** Title, Console, Genre, Publisher, Developer, Critic Score, Regional Sales

## Methodology
1. **Data Cleaning** - Removed irrelevant columns, handled missing values, extracted year
2. **Exploratory Data Analysis** - Visualized sales trends, genre performance, regional breakdown
3. **Feature Engineering** - Defined hit threshold, balanced dataset, encoded categorical variables
4. **ML Model Building** - Trained and compared Logistic Regression, Random Forest, Gradient Boosting
5. **Prediction** - Applied best model to predict GTA VI's commercial success

## Key Findings
- 🏆 **PS2** is the greatest console of all time by total game sales
- 🎯 **Developer identity** is the #1 predictor of a game's success
- 🌍 **North America** accounts for 50.7% of global game sales
- 📈 Physical game sales **peaked in 2008-2009** during the PS3/Xbox 360/Wii era
- 🎵 **Activision** dominates publisher sales through the Call of Duty franchise

## Model Performance
| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 62.6% | 0.646 |
| Random Forest | **78.3%** | **0.852** |
| Gradient Boosting | 74.2% | 0.843 |

## 🎮 GTA VI Prediction
Our Random Forest model predicts GTA VI will be a massive hit:
- **PS5: 94% probability of being a Hit ✅**
- **Xbox Series X: 97% probability of being a Hit ✅**

This aligns with analyst projections of 35-45 million copies 
and over $3 billion in revenue in year one. (Forbes, GameSpot)

## Tools & Technologies
- **Python** - pandas, NumPy, matplotlib, seaborn, scikit-learn
- **Google Colab** - Development environment
- **GitHub** - Version control

## How to Run
1. Clone this repository
2. Open `Video_Game_Sales_Analysis.ipynb` in Google Colab
3. Upload `vgchartz-2024.csv` to Colab
4. Run all cells in order
