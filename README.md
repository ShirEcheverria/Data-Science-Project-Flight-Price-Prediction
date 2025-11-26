# ✈️ Flight Price Prediction Project: Deep Learning & Clustering

This project demonstrates an end-to-end data science pipeline, applying advanced Machine Learning techniques to forecast dynamic flight prices.
<img width="735" height="1222" alt="image" src="https://github.com/user-attachments/assets/b64e5a41-fff3-44d2-aa2c-eeede352e80f" />


## ✨ Project Highlights & Key Capabilities

* **End-to-End Solution:** Successfully executed all stages of a data science project, from data ingestion to model deployment readiness.
* **Core Techniques:** Applied **Deep Neural Network (DNN) Regression**, **Advanced Feature Engineering**, and **Unsupervised Learning (K-Means Clustering)**.
* **Quantitative Insight:** Delivered a data-driven model providing a quantitative framework for analyzing price drivers and segmenting market behavior.

---

## 🎯 Technical Scope & Methodology

| Component | Techniques Applied |
| :--- | :--- |
| **Data Preprocessing** | Handling of **Missing Values**, **Outlier Detection**, and **Categorical Encoding** (One-Hot Encoding). |
| **Feature Engineering** | Extraction of critical temporal features (e.g., flight duration, departure hour) that significantly impacted prediction accuracy. |
| **Data Segmentation** | **K-Means Clustering ($k=2$)** was used to identify two distinct pricing segments (Low/High fare clusters) based on distance and airline type. |
| **Modeling** | Implemented a **Deep Neural Network (DNN) Regressor** (using Keras/TensorFlow) to capture non-linear price prediction. |
| **Evaluation** | Focused on optimization via **Mean Absolute Error (MAE)** and validated model robustness using the **$R^2$ Score**. |

---

## 📈 Results & Performance Summary

| Metric | Result | Interpretation |
| :--- | :--- | :--- |
| **Model Performance ($R^2$ Score)** | **0.9576** | The model demonstrates **exceptionally high reliability**, successfully explaining **95.76%** of the variability in flight prices. |
| **Prediction Error (MAE)** | **6.936** (USD/NIS) | Indicates **high forecast reliability**, as the average prediction error is very low. |
| **Clustering Insight** | Flights in Cluster 1 were, on average, **270.93** (USD/NIS) more expensive than Cluster 0. | Highlights valuable data segmentation for deeper analysis. |

---

## 💻 Tools & Stack

* **Programming:** Python 3.x
* **Data & ML Libraries:** Pandas, NumPy, Scikit-learn (Clustering), **Keras/TensorFlow (Deep Learning)**, Matplotlib/Seaborn (Visualization).
* **Environment:** Jupyter/Colab Notebooks.
