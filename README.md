# Elevate-Labs-ML-Task2
Exploratory Data Analysis (EDA) on the Titanic Dataset for Task 2 of the AI & ML Internship.

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) to understand the underlying structure, patterns, and anomalies of the Titanic dataset using statistics and data visualizations[cite: 1]. 

To maintain an optimized, cloud-ready workspace, the dataset was streamed directly from a live web URL using Pandas rather than being downloaded locally.

## 🛠️ Tools Used
* **Pandas:** For data loading, data manipulation, and generating descriptive statistics[cite: 1].
* **Matplotlib & Seaborn:** For generating static visualizations like histograms, boxplots, and correlation heatmaps[cite: 1].
* **Plotly:** For interactive data visualization and trend analysis[cite: 1].

## 📊 EDA Mini-Guide Implementation

### 1. Summary Statistics
* Used `df.describe()` to capture the mean, median, standard deviation, and quartiles of numerical features like Age and Fare[cite: 1].

### 2. Data Distributions (Histograms & Boxplots)
* Created histograms to check the distribution shape of numeric features[cite: 1]. 
* Implemented boxplots to visually detect extreme data outliers (specifically within the passenger `Fare` column)[cite: 1].

### 3. Feature Relationships
* Generated a correlation matrix heatmap and a pairplot to analyze linear dependencies between variables[cite: 1].

### 4. Key Inferences & Observations
* **Class & Gender Trends:** Passengers in 1st class and female passengers had significantly higher survival rates.
* **Outliers:** The `Fare` column displayed significant right-skewness with extreme outliers paying well above the average ticket price.
* **Missing Data:** Noted missing data values in the `Age` and `Cabin` columns which would require cleaning prior to ML modeling.

