# 🔬 Female Infertility Analysis: Focus on Endometriosis and PCOS

This project explores the critical topic of **female infertility**, with a particular focus on **endometriosis** and **polycystic ovary syndrome (PCOS)**. These two conditions are among the leading causes of infertility in women, yet they are often misunderstood, misdiagnosed, or overlooked in research and clinical practice.

## 🎯 Project Objective

The primary goal of this project is to analyze how **endometriosis** and **PCOS** contribute to infertility using semi real-world data, uncovering correlations, trends, and patterns through comprehensive data exploration, visualization, and machine learning.

---

## 🧠 Background

### 🔹 Endometriosis  
A chronic inflammatory condition where tissue similar to the endometrial lining grows outside the uterus.  
- Symptoms: Chronic pelvic pain, painful periods (dysmenorrhea), infertility  
- Prevalence: Affects ~10% of women of reproductive age globally  
- Source: [Johnson et al., 2022, ESHRE]

### 🔹 Polycystic Ovary Syndrome (PCOS)  
A hormonal disorder causing enlarged ovaries with small cysts on the outer edges.  
- Symptoms: Irregular periods, acne, hirsutism, ovulatory infertility  
- Prevalence: Affects ~8–13% of reproductive-age women  
- Source: [Teede et al., 2018; Lim et al., 2019]

---

## 📊 Data Exploration and Visualization

Data analysis was conducted in the following stages:

### ✅ 1.1 Data Exploration
- Basic statistics
- Missing values
- Feature distributions

### ✅ 1.2 Data Visualization
- **Histogram**: For continuous feature distribution  
- **Correlation Matrix**: To assess linear relationships  
- **KDE & Box Plots**: To compare distributions  
- **Swarm Plot & Violin Plot**: For visualizing class differences  
- **Categorical Feature Distributions**: To understand feature impact on target labels  

---
## 🤖 Model Training

This project applies multiple supervised machine learning algorithms to predict infertility risks related to Endometriosis and PCOS. The following models were implemented and evaluated using **10-Fold Cross-Validation** to ensure robust and reliable results:

### 🧠 Algorithms Used

- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

### 📊 Evaluation Metrics

Each model was assessed using the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

Although model performance was evaluated, the primary focus remained on medical interpretability and understanding the feature correlations with infertility in women.



