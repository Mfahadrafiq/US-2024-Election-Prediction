# 🗳 Predicting the 2024 US Presidential Elections  

## 📌 Overview  
This repository contains a machine-learning pipeline for predicting the **2024 US Presidential Elections** using historical polling data and supervised learning techniques. The project includes:  

- **Data Collection & Feature Engineering** (Polling trends, incumbency, opponent-based features)  
- **Model Training & Evaluation** (XGBoost, Random Forest, Gradient Boosting, Linear Regression)  
- **Vote Share Prediction & Electoral Vote Calculation**  

## 📂 Project Structure  
```
|-- predicting_the_2024_us_presidential_elections.py  # Main script for data processing, training & prediction
|-- data/                                             # Contains historical polling data
|-- models/                                           # Saved models for evaluation
|-- output/                                           # Predicted results & visualizations
```

## 🚀 Installation  
Clone the repository and install dependencies:  
```sh
git clone https://github.com/mfahadrafiq/US-2024-Election-Prediction.git
cd US-2024-Election-Prediction
pip install -r requirements.txt
```

## 🛠️ Usage  
Run the script to process data and train models:  
```sh
python predicting_the_2024_us_presidential_elections.py
```  
View the predicted vote shares & electoral results in the `output/` folder.  

## 🔍 Model Pipeline  
- **Data Collection** (FiveThirtyEight polling data, historical election results)  
- **Feature Engineering** (Polling trends, momentum, incumbency, party influence)  
- **Model Training & Selection** (Linear Regression, XGBoost, Random Forest, Gradient Boosting, Stacking)  
- **Evaluation** (Mean Absolute Error, Winner Prediction Accuracy)  
- **Final Prediction** (Vote share & electoral vote count for each state)  

## 📊 Results  
The models were evaluated across **swing states** using past election cycles (2000-2020). Key findings include:  

- **Best Performing Models:** XGBoost, Random Forest, Gradient Boosting  
- **Most Competitive States:** Pennsylvania, Arizona, Michigan  

### 🏆 Predicted Electoral Vote Count  
| Candidate      | Predicted Electoral Votes | Status       |
|--------------|--------------------------|--------------|
| **Donald Trump**  | **270**                    | 🏆 *Projected Winner* |
| **Kamala Harris** | **268**                    | ❌ *Projected Loser* |

## 📈 Visualization  
- **Polling trends** for each candidate over time  
- **Vote share distributions** per state  
- **Final electoral vote allocation**  
