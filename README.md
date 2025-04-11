# CM2015_Programming_With_Data
# 🥦 Nutrient Analysis & Food Preference – CM2015 Data Science Project

This project explores the relationship between **nutrient intake** and **food preferences** using real-world datasets. It combines **data wrangling, statistical analysis, and machine learning** with **visual storytelling** to uncover patterns in diet behavior.

---


## 🎯 Project Objectives

- Analyze food and nutrient intake patterns across individuals
- Clean and transform datasets using **Pandas** and **NumPy**
- Apply **classification** and **clustering** techniques to uncover dietary groups
- Visualize patterns with **Matplotlib** and **Seaborn**

---

## 🧰 Technologies Used

| Tool/Library    | Purpose                               |
|----------------|----------------------------------------|
| Python (v3.10)  | Main language                         |
| Pandas          | Data cleaning, wrangling              |
| NumPy           | Numerical computation                 |
| Scikit-learn    | Machine learning (KMeans, DecisionTree)|
| Matplotlib      | Static data visualization             |
| Seaborn         | Statistical plotting and styling      |
| Jupyter Notebook| Exploratory coding and analysis       |

---

## 🔍 Key Features

### 🧼 Data Preprocessing
- Merged `nutrients.csv` and `Food_Preference.csv`
- Handled missing values
- Normalized/standardized nutritional data

### 🤖 Machine Learning
- **Classification**: Used Decision Trees to classify dietary types
- **Clustering**: Applied KMeans clustering to group nutrient profiles

### 📊 Data Visualization
- Bar plots for nutrient contribution by food
- Heatmaps for correlation between nutrients
- Scatter plots with cluster coloring

---

## 📈 Sample Visuals

> *(Add visuals if available: e.g., output from seaborn heatmap, matplotlib bar chart, or cluster plot)*

---

## 🧠 Learnings

- Real-world data is messy – preprocessing is 60% of the job!
- Classification models can categorize food preference types with decent accuracy
- Clustering shows patterns in micronutrient groupings by user profiles

---

## 🔧 How to Run the Project

1. Clone the repo:

```bash
git clone https://github.com/yourusername/nutrient-analysis.git
cd nutrient-analysis
```

## 📊 Sample Analysis

```bash
# Nutrient correlation heatmap
sns.heatmap(df.corr(), cmap="YlGnBu", annot=True)

# KMeans clustering
kmeans = KMeans(n_clusters=3)
df['Cluster'] = kmeans.fit_predict(df_scaled)

# Food preference classifier
model = DecisionTreeClassifier()
model.fit(X_train, y_train)
``` 

## 👤 Author
- Losheni Meenakshi Sundaram
- Student,University of London ,Singapore Institute of Management
- 📫 Email: .ms@gmail.comosheni

