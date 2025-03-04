# 📰 Fake News Detection System

The **Fake News Detection System** uses **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to identify fake news articles. It analyzes the content of news articles and predicts whether they are **real** or **fake**. The system is built using **Logistic Regression** and **Random Forest**, achieving **98.27% accuracy**.

This project features a **Streamlit-based UI** that allows users to test news articles and even upload bulk files for verification.

---

## 🚀 Key Features
✔ **Fake News Classification** – Predicts whether the given news article is fake or real.  
✔ **Prediction Probability** – Displays confidence scores for predictions.  
✔ **Bulk Upload** – Allows users to upload a file containing multiple news articles for batch prediction.  
✔ **Interactive UI** – Built with **Streamlit** for a smooth user experience.  

---

## 🛠️ How It Works

### **1️⃣ Dataset Collection**  
- Uses the **Kaggle Fake News Dataset**, which includes news labeled as **real** or **fake**.
- Expanded dataset by incorporating **additional real-world news sources**.

### **2️⃣ Data Preprocessing**  
- Removes **stop words**, **punctuation**, and **irrelevant characters**.
- Applies **stemming** and **lemmatization** for better text normalization.

### **3️⃣ Feature Engineering**  
- Converts text into numerical format using **TF-IDF Vectorization**.

### **4️⃣ Model Building**  
- **Machine Learning Models Used**:
  - **Logistic Regression**
  - **Random Forest**
- Models trained using **Scikit-Learn**, with hyperparameter tuning for optimal performance.

### **5️⃣ Model Evaluation**  
- Evaluated using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**

### **6️⃣ Streamlit Web Application**  
- Simple UI to input a **single news article** or **upload a bulk file**.  
- Displays results with **prediction probability scores**.  

---

## 📊 Model Performance
The model performed **exceptionally well**, achieving high accuracy and recall:

| Metric          | Logistic Regression | Random Forest |
|----------------|--------------------|--------------|
| **Accuracy**   | 98.27%             | 98.5%        |
| **Precision**  | 98%                 | 99%          |
| **Recall**     | 99%                 | 98%          |
| **F1-score**   | 98%                 | 98.5%        |

> *Note: These results are based on our dataset and may vary slightly with different datasets.*

---

## 📌 Sample Predictions

| News Headline                                      | Prediction | Probability |
|----------------------------------------------------|------------|-------------|
| "Government announces new economic policy"       | **Real**   | 97%         |
| "Aliens found in a secret underground base"      | **Fake**   | 99%         |
| "New study reveals benefits of meditation"       | **Real**   | 96%         |
| "NASA confirms the moon is made of cheese"      | **Fake**   | 98%         |

---

## 🚀 Demo and Deployment
The project is deployed on **Streamlit Cloud**. Try it here:  
🔗 **[Live Demo](https://fakenewsdetection-sqkrjjwxcjh9gia5i5ar83.streamlit.app/)**

---
