# 💝 Valentine's Gifts Analysis – Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) on Amazon's Best-Selling Valentine’s Day gifts dataset to uncover trends in pricing, customer reviews, and brand performance. The goal is to extract meaningful insights into consumer purchasing behavior using Python data analysis and visualization libraries.

---

## 📊 Dataset Information

- **Source:** Kaggle  
- **Dataset:** 2024 Amazon Best Sellers: Top Valentine's Gifts  
- **Contents:**  
  The dataset includes information about popular Valentine’s Day products, such as:

  - Product brand name  
  - Product price  
  - Currency  
  - Number of customer reviews  
  - Star ratings  
  - Rating distribution  
  - Product descriptions  

---

## 🎯 Project Objectives

The main objectives of this project are:

- Perform data cleaning and preprocessing on real-world e-commerce data
- Analyze gift price distribution
- Explore relationships between product price and customer reviews
- Identify top-performing brands based on ratings
- Visualize trends using Python visualization libraries

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🔧 Data Cleaning and Preprocessing

The following preprocessing steps were performed:

- Removed columns with excessive missing values
- Renamed columns for better readability
- Filled missing currency values with "$"
- Replaced missing prices with the mean price
- Replaced missing review counts with the median value
- Removed rows with missing brand names

---

## 📈 Analysis Performed

### 1. Price Distribution Analysis
- Histogram of product prices
- Identification of common spending ranges

### 2. Price vs Customer Reviews
- Scatter plot to examine correlation between price and number of reviews

### 3. Brand Rating Analysis
- Comparison of brands based on average ratings
- Visualization of ratings vs review counts

---

## 🔍 Key Insights

- Most Valentine’s gifts are priced under **$20**
- Lower-priced products tend to have more customer reviews
- Highly rated products often have higher engagement
- A few brands dominate the best-seller category

---

## 📂 Project Structure

```
Valentines-Gifts-Analysis/
│
├── EDA_Valentine_Gifts_Analysis.ipynb   # Main analysis notebook
├── valentines_best_sellers.csv         # Dataset file
└── README.md                          # Project documentation
```

---

## ▶️ How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/Valentines-Gifts-Analysis.git
cd Valentines-Gifts-Analysis
```

### Step 2: Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```
EDA_Valentine_Gifts_Analysis.ipynb
```

---

## 📌 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Data Visualization
- Data Interpretation
- Python for Data Science

---

## 🚀 Future Improvements

- Interactive dashboards using Plotly or Streamlit
- Predictive modeling for product ratings
- Sentiment analysis on product reviews
- Automated reporting


