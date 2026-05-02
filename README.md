
# 🍔 Swiggy Delivery Time Analysis

A data analysis project that explores **delivery time patterns, pricing behavior, and efficiency trends** across different cities using real-world Swiggy dataset.

---

## 📌 Project Overview

This project focuses on analyzing food delivery performance by examining:

* Delivery time distribution
* City-wise performance comparison
* Price vs delivery relationship
* Delivery efficiency metrics
* Service consistency across cities

The goal is to extract **actionable insights** that can help improve delivery operations and customer experience.

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas & NumPy
* 📈 Matplotlib & Seaborn
* 📁 Jupyter Notebook / Google Colab

---

## 📂 Dataset

* Dataset used: `swiggy.csv`
* Key features:

  * `city`
  * `price`
  * `delivery_time`

---

## ⚙️ Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Standardized column names

### 2. Data Cleaning

* Removed duplicates
* Handled missing values

### 3. Exploratory Data Analysis (EDA)

* Statistical summary of delivery time
* Distribution analysis

### 4. Outlier Removal

* Used **IQR method** to remove extreme values

### 5. Feature Engineering

* 🚀 Delivery Speed Category (Fast, Medium, Slow)
* 💰 Price Category (Low, Medium, High)
* ⚡ Cost Efficiency (Price / Delivery Time)

### 6. Visualization

Key visualizations include:

* 📊 Delivery time distribution
* 📦 Boxplot of delivery time by city
* 📉 Average delivery time comparison
* 🚦 Delivery speed categories
* 💸 Price vs delivery time scatter plot
* 🔥 Correlation heatmap
* 📏 Consistency (standard deviation by city)
* <img width="430" height="428" alt="image" src="https://github.com/user-attachments/assets/5dd25dec-6b7d-4549-8064-d1b33d23262e" />
<img width="500" height="154" alt="image" src="https://github.com/user-attachments/assets/1d343d6a-5625-41f0-b5fc-c6867b213f8d" />
<img width="320" height="544" alt="image" src="https://github.com/user-attachments/assets/b243bd24-4398-4586-89e2-69efc4317aa8" />
<img width="320" height="546" alt="image" src="https://github.com/user-attachments/assets/00d459df-bcfb-44c3-a4e9-959cde13f4b8" />
<img width="320" height="524" alt="image" src="https://github.com/user-attachments/assets/07fba8f7-64e1-4d69-bd6e-2400512d91da" />
<img width="300" height="446" alt="image" src="https://github.com/user-attachments/assets/1bec993b-f9e4-4557-bb27-9e27b4c873bf" />


---

## 📊 Key Insights

* 📍 Delivery time varies significantly across cities
* 🚀 Most deliveries fall under **medium speed category**
* 💰 Price has **weak correlation** with delivery time
* ⚠️ Some cities show **high inconsistency** in delivery performance
* ❗ Higher price does **not guarantee faster delivery**

---

## 📈 Sample Results

* ⏱️ Average Delivery Time: *calculated dynamically*
* 🥇 Fastest City: *based on mean delivery time*
* 🐢 Slowest City: *based on mean delivery time*
* 📦 90% deliveries completed under a threshold time

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/swiggy-delivery-analysis.git

# Navigate to project folder
cd swiggy-delivery-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run the script / notebook
```

---

## 📌 Future Improvements

* Add machine learning model to predict delivery time
* Incorporate real-time traffic or distance data
* Build interactive dashboard using Power BI / Streamlit
* Perform time-series analysis

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---
