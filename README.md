This repository contains a collection of Jupyter Notebook assignments completed as part of coursework/projects.  
It is organized into **Part A** and **Part B**, covering exploratory data analysis, visualization, statistical methods, and predictive modeling.  
Two main datasets were analyzed across these parts, leading to different insights.

---

## 📂 Contents

### Part A – Foundations & Exploratory Analysis
1. **Part A1** – Data Cleaning & Preprocessing  
   - Dataset: **[Dataset 1: Retail Sales/Transactions]**  
   - Tasks: Handling missing values, detecting outliers, feature transformations  
   - **Insights**:  
     - ~8% of records had missing transaction amounts, primarily from one branch.  
     - Outlier detection revealed high-value purchases that contributed disproportionately to revenue.  
     - Normalization improved comparability across store locations.  
   - **Skills**: pandas, numpy, feature engineering  

2. **Part A2** – Exploratory Data Analysis (EDA)  
   - Dataset: **Retail Sales**  
   - Tasks: Descriptive statistics, visualization, correlation analysis  
   - **Insights**:  
     - Sales peaked during weekends and festive months.  
     - Positive correlation between store size and average revenue.  
     - Customer demographics (age group 25–40) showed the highest spend.  
   - **Skills**: matplotlib, seaborn, descriptive analysis  

3. **Part A3** – Statistical Modeling  
   - Dataset: **Retail Sales**  
   - Tasks: Hypothesis testing, ANOVA, regression basics  
   - **Insights**:  
     - Significant differences in mean revenue between store categories (p < 0.05).  
     - Simple regression explained ~65% variance in sales from marketing spend.  
   - **Skills**: scipy, statsmodels, regression diagnostics  

4. **Part A4** – Probability & Distributions  
   - Dataset: **Retail Sales**  
   - Tasks: Normal distribution fitting, simulations, sampling methods  
   - **Insights**:  
     - Transaction values followed a log-normal distribution, not normal.  
     - Bootstrapping provided stable confidence intervals for average spend.  
   - **Skills**: numpy, scipy.stats  

---

### Part B – Applied Machine Learning
1. **Part B1** – Supervised Learning: Regression  
   - Dataset: **[Dataset 2: Housing/Real Estate]**  
   - Tasks: Linear Regression, Ridge/Lasso regularization  
   - **Insights**:  
     - Key predictors of price: square footage, number of bedrooms, and location.  
     - Ridge regression reduced overfitting compared to OLS.  
   - **Skills**: scikit-learn, regression modeling  

2. **Part B2** – Supervised Learning: Classification  
   - Dataset: **Housing**  
   - Tasks: Logistic Regression, Decision Trees, Random Forest  
   - **Insights**:  
     - Decision Trees provided intuitive splits but overfit on small data.  
     - Random Forest achieved ~88% accuracy in predicting “high-priced” vs “low-priced” houses.  
     - Important features: location score, size, proximity to city center.  
   - **Skills**: scikit-learn, ROC/PR analysis  

3. **Part B3** – Time Series Analysis  
   - Dataset: **Housing Transactions (time series)**  
   - Tasks: ARIMA/SARIMA, moving averages, trend/seasonality  
   - **Insights**:  
     - Clear seasonal trends: sales peak in Q2 every year.  
     - SARIMA model outperformed ARIMA in capturing seasonal patterns.  
   - **Skills**: statsmodels, pandas datetime  

4. **Part B4** – Neural Networks & Advanced Models  
   - Dataset: **Housing**  
   - Tasks: Keras-based neural networks, hyperparameter tuning  
   - **Insights**:  
     - Neural network models marginally improved prediction RMSE (~5% better than Ridge).  
     - Feature scaling crucial for stable training.  
   - **Skills**: TensorFlow/Keras, model evaluation  

---
