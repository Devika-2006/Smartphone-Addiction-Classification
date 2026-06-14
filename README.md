# 📱 Smartphone Addiction Classification using Machine Learning

## 📝 Project Overview

In today's digital world, smartphones have become an essential part of daily life. However, excessive smartphone usage can lead to addiction, affecting productivity, sleep quality, and overall well-being.

This project uses **Machine Learning Classification** to predict whether a person is **Addicted** or **Not Addicted** to smartphones based on their daily usage behavior. By analyzing factors such as screen time, social media usage, gaming habits, notifications received, and sleep duration, the model can accurately classify smartphone addiction levels.

---

## 🎯 Objective

The main objectives of this project are:

* Analyze smartphone usage patterns.
* Predict whether a user is addicted to smartphones.
* Identify the most influential factors contributing to addiction.
* Apply Machine Learning concepts to a real-world behavioral dataset.

---

## 🛠️ Technologies Used

| Technology   | Purpose                           |
| ------------ | --------------------------------- |
| Python       | Programming Language              |
| Pandas       | Data Manipulation                 |
| NumPy        | Numerical Computation             |
| Scikit-Learn | Machine Learning                  |
| Matplotlib   | Data Visualization                |
| Seaborn      | Data Visualization                |
| Google Colab | Development Environment           |
| GitHub       | Version Control & Project Hosting |

---

## 📊 Dataset Description

The dataset used in this project contains **3000 records** representing realistic smartphone usage behavior.

### Features (Input Variables)

| Feature                  | Description                             |
| ------------------------ | --------------------------------------- |
| ⏱️ Screen_Time_Hours     | Total daily smartphone usage time       |
| 💬 Social_Media_Hours    | Time spent on social media applications |
| 🎮 Gaming_Hours          | Time spent playing mobile games         |
| 🔔 Notifications_Per_Day | Number of notifications received daily  |
| 💤 Sleep_Hours           | Average sleep duration per day          |

### Target Variable

| Class | Description  |
| ----- | ------------ |
| 0     | Not Addicted |
| 1     | Addicted     |

---

## 🔄 Project Workflow

```text
Dataset Generation
        ↓
Data Exploration
        ↓
Data Preprocessing
        ↓
Exploratory Data Analysis (EDA)
        ↓
Correlation Analysis
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Prediction
        ↓
Performance Evaluation
        ↓
Model Saving
```

---

## 📈 Exploratory Data Analysis (EDA)

During the analysis phase, several patterns were observed:

### Key Observations

✅ Screen Time showed the strongest positive relationship with addiction.

✅ Social Media Usage significantly influenced addiction levels.

✅ Gaming Hours had a moderate impact on smartphone addiction.

✅ Sleep Hours showed a negative correlation with addiction.

✅ Users with higher screen time and lower sleep duration were more likely to be classified as addicted.

---

## 🤖 Model Building

A **Random Forest Classifier** was used to build the classification model.

### Why Random Forest?

* High accuracy and reliability.
* Handles large datasets efficiently.
* Reduces overfitting compared to a single Decision Tree.
* Works well with numerical features.
* Provides strong classification performance.

---

## 📊 Model Performance

The model achieved excellent results on the testing dataset.

| Metric    | Score      |
| --------- | ---------- |
| Accuracy  | **95.33%** |
| Precision | **96.48%** |
| Recall    | **95.36%** |
| F1-Score  | **95.92%** |

---

## 🏆 Project Results

The Random Forest Classifier successfully classified smartphone addiction behavior with high accuracy.

### Classification Report

| Class            | Precision | Recall | F1-Score |
| ---------------- | --------- | ------ | -------- |
| Not Addicted (0) | 0.94      | 0.95   | 0.95     |
| Addicted (1)     | 0.96      | 0.95   | 0.96     |

### Overall Performance

* ✅ Accuracy: 95.33%
* ✅ Precision: 96.48%
* ✅ Recall: 95.36%
* ✅ F1-Score: 95.92%

The model correctly classified **572 out of 600 test samples**.

---

## 🧪 Confusion Matrix Analysis

|                     | Predicted Not Addicted | Predicted Addicted |
| ------------------- | ---------------------- | ------------------ |
| Actual Not Addicted | 243                    | 12                 |
| Actual Addicted     | 16                     | 329                |

### Interpretation

* True Negatives: 243
* False Positives: 12
* False Negatives: 16
* True Positives: 329

The confusion matrix indicates that the model performs consistently well across both classes.

---

## 💡 Key Findings

📱 Screen Time is the strongest indicator of smartphone addiction.

🌐 Social Media Usage contributes significantly to addiction behavior.

🎮 Gaming Hours influence addiction but less than social media usage.

💤 Lower sleep duration is associated with higher addiction levels.

📊 The model demonstrates that behavioral data can effectively predict smartphone addiction.

---

## 📂 Project Structure

```text
Smartphone-Addiction-Classification/

├── screenshots/
│   ├── addiction_distribution.png
│   ├── correlation_heatmap.png
│   ├── model_accuracy.png
│   └── confusion_matrix.png

├── smartphone_addiction.ipynb
├── smartphone_addiction.csv
├── addiction_classifier.pkl
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

* Implement Hyperparameter Tuning.
* Compare multiple Machine Learning algorithms.
* Build a Streamlit Web Application.
* Deploy the model online.
* Use real-world smartphone usage data.
* Improve model performance through feature engineering.

---

## 🎓 Learning Outcomes

Through this project, I learned:

* Data Collection and Preprocessing
* Exploratory Data Analysis (EDA)
* Correlation Analysis
* Classification Algorithms
* Random Forest Classifier
* Model Evaluation Metrics
* Confusion Matrix Analysis
* Model Saving and Loading
* GitHub Project Documentation

---

## 📋 Requirements

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 👤 Author

**Devika S**

Computer Science Student | Machine Learning Enthusiast

---

## ⭐ Conclusion

This project demonstrates how Machine Learning can be used to identify smartphone addiction based on behavioral patterns. The Random Forest Classifier achieved **95.33% accuracy**, showing strong performance in predicting addiction status and highlighting the relationship between smartphone usage habits and digital well-being.
