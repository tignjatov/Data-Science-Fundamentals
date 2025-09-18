# Data Science Fundamentals

This repository contains the final project for the **Data Science Fundamentals** course.  
The project applies the complete data science pipeline on the **World Bank Dataset** (from Kaggle), covering socio-economic and environmental indicators across countries.

## Dataset
-  Source: [World Bank Dataset on Kaggle] (https://www.kaggle.com/datasets/johnymariah/world-bank-data-etl)
-  Processed dataset used in this project is available here: [Google Drive Link] (https://drive.google.com/drive/folders/1tk2xSzN4cwKKa6_PpumHEVToYK4M3lev?usp=sharing)
- Indicators: GDP, population, unemployment rate, CO₂ emissions, access to electricity, life expectancy, etc.  
- Data was cleaned, preprocessed, and analyzed using Python (pandas, numpy, matplotlib, seaborn, scikit-learn, etc.).

## Project Phases

### 1. Data Exploration & Visualization
- Population distribution (bar plots)  
- Life expectancy vs. GDP (scatter plots)  
- Unemployment trends (heatmaps)  
- CO₂ emissions vs. electricity access (boxplots)  
- GDP trends over time (line plots)  

### 2. Data Preparation & EDA
- Handling missing values and scaling features  
- Distribution analysis with histograms  
- Outlier detection (IQR method)  
- Correlation heatmaps  
- Dimensionality reduction with **PCA** and **t-SNE**

### 3. Statistical Analysis
- Normality testing (Shapiro-Wilk)  
- Group comparison (Mann-Whitney U-test)  
- Effect size (Cohen’s d)  
- Confidence intervals  

### 4. Predictive Modeling
- **Regression**: Linear regression to predict continuous life expectancy  
- **Classification**: Logistic Regression & SVM to classify “Low” vs. “High” life expectancy  

### 5. Advanced Machine Learning
- **K-Means clustering** for grouping countries  
- **Decision Tree classifier** for life expectancy categories  
- **Neural Network**: Feed-forward network with hidden layers and dropout regularization → accuracy improved up to **91%**

## Repository Structure
- `Faza1.ipynb`, `Faza2.ipynb`, `Faza3.ipynb` – Jupyter notebooks (data exploration, ML models, analysis)  
- `Osnovi nauke o podacima objašnjenje.docx` – Full report with detailed explanations  
- `Osnovi nauke o podacima projekat.pptx` – Project presentation  

## Key Takeaways
- Learned the full data science workflow: preprocessing → visualization → statistical testing → machine learning → evaluation  
- Applied both **classical ML** and **deep learning** approaches  
- Demonstrated ability to analyze real-world socio-economic data and extract insights  


*This project demonstrates practical skills in data analysis, visualization, statistical inference, and machine learning.*
