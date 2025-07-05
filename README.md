# 🌸 Iris Classification using Random Forest – SageMaker Studio Lab

This project implements a complete machine learning pipeline to classify iris flower species using the classic Iris dataset. The workflow is built and tested on **Amazon SageMaker Studio Lab**, simulating an end-to-end ML project lifecycle from preprocessing to evaluation.

---

## 📌 Project Overview

* **Objective:** Predict the iris species (`Setosa`, `Versicolor`, `Virginica`) based on sepal and petal dimensions.
* **Algorithm Used:** Random Forest Classifier
* **Platform:** SageMaker Studio Lab (CPU instance)
* **Dataset:** Iris dataset (150 samples, 4 features, 3 classes)

---

## 🔧 Tools & Libraries

* Python 3
* Scikit-learn
* Pandas
* NumPy
* Matplotlib / Seaborn (optional for visualization)
* SageMaker Studio Lab (environment)

---

## 🧪 Pipeline Steps

1. **Import Dataset**
2. **Data Exploration & Visualization**
3. **Preprocessing & Feature Selection**
4. **Train-Test Split**
5. **Model Training (Random Forest)**
6. **Prediction & Evaluation**

   * Accuracy
   * Confusion Matrix
   * Classification Report

---

## 🎯 Results

* **Model Used:** Random Forest Classifier
* **Accuracy Achieved:** 90%
* **Training Time:** Under 1 second (due to small dataset)

---

## 📁 Folder Structure

```
 ├️ 📄 iris_classifier_sagemaker.ipynb
 ├️ 📄 README.md
```

---

## 🚀 How to Run

1. Open [SageMaker Studio Lab](https://studiolab.sagemaker.aws/)
2. Upload `iris_classifier.ipynb`
3. Choose **CPU runtime**
4. Run each cell to execute the pipeline

---

## 🧐 Learning Outcomes

* End-to-end pipeline construction using `Scikit-learn`
* Using Random Forest for multi-class classification
* Model evaluation techniques and interpretation
* Hands-on with **SageMaker Studio Lab** (AWS-hosted Jupyter environment)

---

## 🔮 Future Work

* Integrate with AWS SageMaker SDK for deployment
* Compare with other models like SVM, XGBoost, KNN
* Add interactive dashboard using Gradio or Streamlit
* Perform hyperparameter tuning for improved accuracy
* Expand to more complex, real-world datasets
