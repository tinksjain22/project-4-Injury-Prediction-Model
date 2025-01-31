# NFL Injury and Draft Success Prediction

## 📌 Project Overview  
This project aims to leverage historical NFL data and machine learning models to predict two key outcomes:  

1. **Player Injuries** – Identifying patterns and factors contributing to injuries, helping teams mitigate risks and optimize player management.  
2. **Draft Success** – Utilizing NFL Combine metrics to predict the likelihood of players being drafted, aiding teams in decision-making.  

## 📊 Data Sources  
The dataset consists of three key components:  

- **Injury Records**  
  - 105 injury records  
  - 100 unique players  
  - Key columns: `PlayerKey`, `GameID`, `PlayKey`  
  - 28 missing `PlayKey` values  

- **PlayList**  
  - 250 players  
  - 5,712 games  
  - 267,005 plays  
  - Key columns: `PlayerKey`, `GameID`, `PlayKey`  

- **NFL Combine Data**  
  - 3,476 unique players (2009-2019)  
  - Key columns: `Drafted`, `Player_Type`, `Position_Type`, `Age`, `School`  

## 🔬 Methodology  

### 🔹 Data Preprocessing  
- Handling missing values and outliers  
- Feature engineering: binning, one-hot encoding, and scaling  

### 🔹 Machine Learning Approach  
- **Model Selection**: Injury and draft prediction models using ML techniques  
- **Training & Optimization**: Data splitting, hyperparameter tuning  
- **Evaluation Metrics**: Accuracy, Precision, and Recall  

## 🚀 Key Findings  
- **Injury Prediction**: Machine learning can help forecast injuries, improving player safety.  
- **Drafting Prediction**: Teams' drafting decisions can be predicted based on NFL Combine statistics.  
- **Future Scope**: Expanding ML capabilities to other areas of sports analytics.  

## 👥 Contributors  
- Kelly He  
- Philip Rex Peters  
- Samuel Williamson  
- Tinkle Jain  
- Saswata Chakraborty  

## 🎯 Acknowledgments  
We appreciate the availability of NFL data sources and machine learning frameworks that made this research possible.  

## 📬 Reference
With assistance from **ChatGPT**.  

 
