# FIFA20-Player-Analytics
Data Science project for analyzing FIFA 20 player statistics using Python. The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, visualization, and player segmentation using clustering algorithms to discover meaningful insights from football player data.

# ⚽ FIFA 20 Player Analytics using Data Science

## 📌 Project Overview

The FIFA 20 Player Analytics project focuses on analyzing football player data from the FIFA 20 dataset to uncover meaningful insights into player characteristics, performance, and attributes. The project demonstrates a complete Data Science workflow, including data cleaning, preprocessing, exploratory data analysis (EDA), visualization, feature engineering, and unsupervised machine learning.

The project applies clustering techniques to group similar players based on their technical, physical, and overall performance attributes. Various visualizations are used to understand player distributions, relationships among features, and patterns hidden within the dataset.

---

## 🎯 Objectives

- Perform comprehensive Exploratory Data Analysis (EDA)
- Clean and preprocess the FIFA 20 dataset
- Handle missing values and inconsistent data
- Perform feature engineering
- Analyze player performance and attributes
- Visualize player statistics and distributions
- Apply clustering algorithms for player segmentation
- Generate meaningful business insights from player data

---

## 📂 Dataset Information

The dataset contains detailed information about FIFA 20 players including personal details, physical attributes, technical skills, and performance ratings.

### Features

- Player Name
- Age
- Nationality
- Club
- Position
- Preferred Foot
- Weak Foot
- Skill Moves
- Height
- Weight
- Overall Rating
- Potential
- Value
- Wage
- Pace
- Shooting
- Passing
- Dribbling
- Defending
- Physical
- Work Rate
- International Reputation
- Contract Information
- Player Traits
- Goalkeeping Attributes
- Technical Attributes

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

- Dataset overview
- Data type inspection
- Missing value analysis
- Statistical summary
- Feature distribution analysis
- Player age distribution
- Overall rating distribution
- Position-wise player analysis
- Preferred foot analysis
- Nationality analysis
- Correlation heatmap
- Pairwise feature analysis
- Outlier detection
- Data visualization

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Removing unnecessary columns
- Feature engineering
- Converting categorical variables
- Feature selection
- Standardization using StandardScaler
- Preparing data for clustering

---

## 🤖 Machine Learning Models

The following clustering algorithms were implemented and compared:

- K-Means Clustering
- Hierarchical Clustering
- Agglomerative Clustering
- DBSCAN Clustering

The optimal number of clusters for K-Means was determined using the Elbow Method.

---

## 📈 Analysis & Evaluation

The project includes:

- Elbow Method for optimal cluster selection
- Cluster visualization
- Cluster profiling
- Feature importance analysis
- Correlation analysis
- Player segmentation
- Performance comparison across clusters

---

## 📊 Project Workflow

1. Import Libraries
2. Load FIFA 20 Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Feature Scaling
8. Clustering Analysis
9. Cluster Evaluation
10. Visualization
11. Player Segmentation
12. Conclusion

---

## 📁 Project Structure

```
FIFA20-Player-Analytics/
│
├── data/
│   └── players_20.csv
│
├── notebook/
│   └── FIFA20_Analysis.ipynb
│
├── images/
│   ├── age_distribution.png
│   ├── overall_rating.png
│   ├── correlation_heatmap.png
│   ├── elbow_method.png
│   ├── player_clusters.png
│   └── cluster_visualization.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/TanmayPatel143/FIFA20-Player-Analytics.git
```

### 2. Navigate to the project folder

```bash
cd FIFA20-Player-Analytics
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run

```
FIFA20_Analysis.ipynb
```

---

## 📌 Results

- Successfully cleaned and preprocessed the FIFA 20 dataset.
- Performed comprehensive Exploratory Data Analysis (EDA).
- Generated meaningful visualizations for player attributes.
- Applied feature engineering and feature scaling.
- Implemented multiple clustering algorithms.
- Identified meaningful player groups using K-Means Clustering.
- Compared clustering techniques and analyzed player segments.
- Generated valuable insights into football player performance and characteristics.

---

## ⚠️ Challenges Faced

- Handling missing values across multiple player attributes.
- Removing redundant and irrelevant features.
- Managing high-dimensional player data.
- Selecting meaningful features for clustering.
- Determining the optimal number of clusters.
- Interpreting cluster characteristics for player segmentation.

---

## 🔮 Future Improvements

- Apply Principal Component Analysis (PCA) for dimensionality reduction.
- Build a Player Recommendation System.
- Develop a Player Value Prediction model.
- Create an interactive dashboard using Streamlit.
- Deploy the project using Flask or FastAPI.
- Explore advanced clustering algorithms and deep learning techniques.

---

## 👨‍💻 Author

**Darsh Patel**

GitHub: https://github.com/Darsh5202

