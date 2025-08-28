# Granify Classification Analysis

## 🏗️ Project Context
This was a research project developed as teamwork for the third term of the Post-Degree Diploma in Data Analytics in Langara College.

## 📌 Project Overview 
This project analyzes session-level user data from an e-commerce platform to evaluate the effectiveness of different marketing strategies. Using exploratory data analysis, data visualization, and machine learning models, the goal was to understand user behavior, assess ad performance, and derive actionable insights to optimize marketing campaigns.

## 🎯 Objective  
- Evaluate the effectiveness of marketing strategies based on session-level interactions.
- Compare treatment vs control groups to measure the impact of ad exposure.
- Identify high-performing ads and optimal timing for user engagement.
- Build predictive models to classify potential responders and guide targeted marketing efforts.

## 🛠 Tools & Technologies  
- **Language:** Python 
- **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Plotly`, `JoyPy`
- **Machine Learning:** Scikit-learn, XGBoost, Random Forest, Logistic Regression, SMOTE
- **Version Control:** Github

## 📊 Key Steps  
1. **Data Preparation**  
   - Removed duplicates, handled categorical encoding, and extracted day/hour variables.  
   - Final dataset: 11,423 rows × 9 features.  

2. **Exploratory Data Analysis (EDA)**  
   - Identified class imbalance: ~96\% non-responses vs 4\% responses.
   - Analyzed ad performance, response rates, and time-based trends.  

3. **Data Visualization**  
   - Heatmaps, correlation funnels, hierarchical clustering, and time-response plots. 

4. **Modelling & Evaluation**  
   - Baseline models: Logistic Regression, Random Forest, XGBoost.
   - Applied SMOTE for class imbalance and hyperparameter tuning for optimization.
   - Compared models using accuracy, recall, AUC, and confusion matrices.

5. **Key Findings**
   - Random Forest achieved the best overall performance with 94\% accuracy and an AUC of 0.86 after tuning.
   - Ad scheduling insights: highest responses occur between 1 AM–4 AM.
   - Personalized ad targeting improves conversion potential.
   - Ad 1 generates the highest conversions (~11\%).
   - Prioritize budget allocation toward high-performing ads

## 🚀 Results  

| **Model**            | **Accuracy** | **AUC** | **Recall (Positive)** | **Key Insight**                                |
|----------------------|-------------|---------|-----------------------|----------------------------------------------|
| Logistic Regression  | 71\%         | 0.78    | **75\%**               | Best for maximizing positive detection      |
| Random Forest       | **94\%**     | **0.86**| 25\%                   | Best balance between accuracy & recall     |
| XGBoost            | 94\%         | 0.84    | 16\%                   | Consistent performance, but weaker recall |


## 📂 Repository Structure  
```
├── Data/              # Raw data
├── Src/           # Jupiter Notebook scripts for analysis and modelling
├── Documentation/   # Final project report and presentation
└── README.md          # Project description
```

## 🙌 Acknowledgments  
Developed by:  
- Javier Merino  
- Meyliani Sanjaya  
- Angeli De los Reyes  
- Nay Zaw Lin  
