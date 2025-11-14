# 🚢 Machine Learning from Disaster

This repository documents my solution for the **Kaggle “Titanic: Machine Learning from Disaster”** challenge - https://www.kaggle.com/competitions/titanic.

---

## Overview

The objective of this project is to predict whether a passenger survived the Titanic disaster - a classic binary classification problem. Using the historical manifest data, the analysis focuses on uncovering the socio-economic and situational factors that influenced survival likelihood.

My final optimized **Random Forest** model achieved an accuracy score of **0.78708**, placing the solution in the **top 12%** of more than **16,000** public leaderboard submissions.

---

## Core Project Steps

Main stages of the workflow include:

- **Exploratory Data Analysis:** Reviewing data quality, distributions, and relationships.
- **Thoughtful Data Cleaning:** Handling missing values using contextual imputation (e.g., inferring age from extracted social titles).
- **Feature Engineering:**  
  - Extracting **Title** from passenger names  
  - Deriving **Deck** information from cabin codes  
  - Creating **Age_Group** via intelligent binning  
- **Modeling & Optimization:** Training multiple models, evaluating performance, and tuning the final Random Forest classifier.
