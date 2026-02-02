# 💖 End-to-End Customer Churn Prediction — A Data Science Story

> _"Behind every churned customer is an untold story.  
Data science helps us listen before they leave."_  

---

## 🌍 Project Overview

This project focuses on predicting **customer churn** in the telecom industry using data-driven insights and machine learning.  
The goal is to identify customers who are likely to discontinue their services and understand *why* they might leave — enabling proactive retention strategies.

By combining **data analysis**, **ML pipelines**, and **explainable AI**, this project bridges the gap between raw data and meaningful business action.

---

## ❓ What is Customer Churn?

**Customer churn** occurs when customers or subscribers stop using a company’s products or services.  
In the **telecom industry**, this is a serious concern as customers can easily switch between service providers offering better pricing, plans, or network quality.

📉 **Why it matters:**  
Acquiring a new customer is often **5x more expensive** than retaining an existing one.  
Telecom companies face annual churn rates between **15%–25%**, and each lost customer impacts both revenue and market position.

🧠 **How data science helps:**  
With millions of customers, it’s impossible to manually identify who’s about to leave.  
By analyzing customer demographics, usage patterns, and service data, machine learning models can **predict churn probability** — allowing companies to focus retention efforts where they matter most.

This predictive approach helps:
- Lower customer acquisition costs  
- Increase customer lifetime value  
- Improve loyalty through personalized retention offers  

Ultimately, the key to success in telecom lies in **understanding the customer before they churn**.

---

## 🎯 Project Objectives

- Calculate the **percentage of churned vs retained customers**
- Analyze key **drivers of churn** such as tenure, contract type, and monthly charges
- Build and compare multiple **machine learning models** to classify customers accurately
- Derive **business insights** that can guide targeted retention strategies

---

## 🧠 Workflow

| Step | Description |
|------|--------------|
| **1. EDA** | Explored tenure, contract type, and charges to find churn patterns |
| **2. Data Cleaning** | Fixed data type issues and handled missing values |
| **3. ML Pipeline** | Built a clean `ColumnTransformer + Pipeline` architecture |
| **4. Modeling** | Trained Logistic Regression, Random Forest, and Gradient Boosting |
| **5. Evaluation** | Compared models using ROC-AUC and ROC curves |
| **6. Explainability** | Used SHAP to interpret global and individual predictions |
| **7. Insights** | Turned findings into actionable business recommendations |

---

## 📊 Key Visuals

### 🔹 Churn Distribution
![Churn Distribution](assets/churn_dist.png)

### 🔹 Contract Type vs Churn
![Contract vs Churn](assets/contract_vs_churn.png)

### 🔹 ROC Curve Comparison
![ROC Curve](assets/roc_curve.png)

### 🔹 SHAP Explainability
![SHAP Plot](assets/shap_plot.png)

---

## 💡 Business Insights

> 🧩 **Key Findings:**
>
> - Customers on **month-to-month contracts** are far more likely to churn than those on longer commitments.  
> - **High monthly charges** correlate with higher churn risk.  
> - **Long-tenure customers** tend to remain loyal.  
> - **Senior citizens and paperless billing users** also show unique churn patterns.  
>
> 🧭 **Recommendations:**
> - Offer **discounted upgrades or loyalty programs** for short-tenure, high-charge customers.  
> - Introduce **bundled services or long-term contracts** to improve stickiness.  
> - Target churn-prone segments with **personalized offers and better customer support**.  

---

## ⚙️ Tech Stack

- **Language:** Python 🐍  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, shap  
- **Tools:** Jupyter Notebook, GitHub  
- **Visualization:** Seaborn, Matplotlib, SHAP plots  

---

## 🚀 Model Performance

| Model | Accuracy | ROC-AUC |
|--------|-----------|----------|
| Logistic Regression | 0.80 | 0.83 |
| Random Forest | 0.85 | 0.86 |
| Gradient Boosting | **0.86** | **0.87** |

> ✅ Gradient Boosting achieved the highest performance, balancing accuracy and interpretability.

---

## 🔍 SHAP Explainability Example

The SHAP plot below explains how each feature influences a single prediction —  
why the model believes a specific customer will churn or stay.

![SHAP Waterfall Plot](assets/shap_plot.png)

> Blue bars reduce churn probability (retention signals).  
> Red bars increase churn probability (risk signals).

---

## 🧾 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

**requirements.txt**
```
pandas
numpy
matplotlib
seaborn
scikit-learn
shap
jupyterlab
```

---

## 💬 Final Thoughts

This project represents more than a churn model —  
it’s a step toward **understanding customers through data empathy**.

> “Data science isn’t about predicting the future —  
it’s about empowering people to change it.”

Through this project, I learned to:
- Integrate clean ML pipelines for reproducibility  
- Balance technical performance with business storytelling  
- Build explainable models that earn stakeholder trust  

---

## ✨ Author

**Naman Bansal**  
💼 Data Science Enthusiast | ML Learner | Business Analyst  
📫 [LinkedIn](#https://www.linkedin.com/in/naman-bansal-01969a325?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

⭐ *If you found this project insightful, don’t forget to star the repository!* ⭐
