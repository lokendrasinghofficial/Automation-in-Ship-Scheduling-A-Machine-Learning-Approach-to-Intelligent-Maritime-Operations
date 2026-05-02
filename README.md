#  Automation in Ship Scheduling

### A Machine Learning Approach to Intelligent Maritime Operations

##  Overview

This project focuses on automating ship scheduling in maritime ports using machine learning. It predicts vessel waiting times and assigns priority scores to optimize berth allocation, reduce congestion, and improve operational efficiency.

The system uses historical AIS (Automatic Identification System) data and applies predictive modeling to enable **data-driven and intelligent scheduling decisions**.


---

##  Objectives

* Predict ship waiting time using machine learning
* Optimize ship scheduling and berth allocation
* Reduce port congestion and delays
* Improve operational efficiency and resource utilization

---

##  Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Scikit-learn
  * Matplotlib / Seaborn
* **Model Used:** Random Forest Regressor

---

##  Methodology

1. **Data Collection**

   * AIS maritime data with ship movements and port operations

2. **Data Preprocessing**

   * Cleaning, encoding, normalization
   * Feature selection and engineering

3. **Feature Engineering**

   * Congestion Ratio
   * Seasonal Patterns
   * Peak Week Indicator

4. **Model Training**

   * RandomForestRegressor used to predict waiting time

5. **Priority Scoring**

   * Ships ranked based on predicted waiting time and operational features

6. **Scheduling Algorithm**

   * Ships scheduled using optimized priority-based logic

---

##  Model Performance

* **Accuracy:** 98.5%
* **MAE:** 1.14
* **R² Score:** 1.00
* **Precision:** 0.98
* **Recall:** 0.97
* **F1 Score:** 0.89

These results indicate strong predictive performance and reliable scheduling decisions.

---

##  Features

* Predicts ship waiting time
* Generates priority scores for scheduling
* Supports real-time scheduling adjustments
* Visualizes feature importance and model performance
* Scalable for different port sizes

---

##  Project Structure

```
├── shipschedulingrp.py      # Main ML model and scheduling logic
├── AISData.csv              # Dataset (not included / optional)
├── README.md                # Project documentation
├── model.pkl                # Saved trained model
```

##  How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/ship-scheduling-ml.git

# Install dependencies
pip install -r requirements.txt

# Run the script
python shipschedulingrp.py
```

---

##  Results & Insights

* Reduced ship waiting time significantly
* Improved berth utilization
* Enabled dynamic scheduling based on real-time data
* Achieved high accuracy with minimal error

---

##  Real-World Impact

* Smarter port operations
* Reduced fuel consumption and emissions
* Faster ship turnaround
* Scalable for global maritime logistics

---

##  Future Work

* Integration with real-time AIS streaming
* Use of Reinforcement Learning for adaptive scheduling
* Improved interpretability using SHAP/LIME
* Multi-port coordination system

---

##  Authors

* Lokendra Singh
* Kartik Dogra
* Sania Joshi
* Rohan Singh
* Nikhil Kumar
* Navjot Singh

---
