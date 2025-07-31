# 🩺 Breast Cancer Risk Predictor Dashboard (Power BI)

## 🎯 Transparent AI-Powered Cancer Diagnosis using Logistic Regression + SHAP

---

## # Overview

This Power BI dashboard uses an interpretable AI approach to detect breast cancer. It combines:

- A reliable **Logistic Regression** classifier
- **SHAP (SHapley Additive exPlanations)** for transparent feature attribution
- Real-time interactive **Power BI visual analytics**

Built to help **clinicians, radiologists, and healthcare leaders** make fast, accurate, and trustworthy diagnostic decisions.

---

## # Dataset

- 📊 **Source**: [UCI Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))
- 👩‍⚕️ **Patients**: 114
- 🧬 **Features**: 30 numeric diagnostic measures (mean, worst, SE)
- 🎯 **Target**: Benign (0) vs. Malignant (1)

---

## # Dashboard KPIs

| Metric                        | Value           |
|------------------------------|-----------------|
| ✅ Prediction Accuracy        | **98.2%**       |
| 🔍 Average Risk Probability   | **38.9%**       |
| 🔬 Malignant Predictions      | **41 patients** |
| 📊 Total Patients             | **114**         |
| 💥 Top Global SHAP Feature    | `texture_worst` |

---

## # Dashboard Pages

### 🔹 Page 1: Global SHAP Drivers
- Shows **top global features** impacting predictions.
- Bar chart built on **sum of SHAP values**, not model coefficients.
- Top feature: **`texture_worst`**

### 🔹 Page 2: Patient-Level Explanation
- Select any patient to explore their:
  - Diagnosis
  - Prediction confidence
  - SHAP waterfall: pushing toward benign/malignant
- Enhances **clinical trust** and **patient-specific storytelling**.

### 🔹 Page 3: SHAP Clustering Segments
- Patients grouped into **behavioral SHAP clusters**.
- Cluster-level KPIs:
  - Top SHAP feature
  - Average risk %
  - Malignant rate %
  - SHAP scatter & feature maps

---

## # Conclusion

- The model correctly predicted **98.2% of all cases**, including **all 41 malignant cases**.
- SHAP global + local explainability makes results **clinically interpretable**.
- Ideal for **clinical decision support, diagnostics labs, and digital health startups**.

---

## # Business Impact (2025)

1. 💸 **Cost Reduction**  
   Early detection of malignant cases can save **$11K–$17K per patient** on average.

2. 💡 **Revenue Opportunity**  
   A 10% improvement in early detection could lead to **$500K+ annual savings** per mid-sized hospital (KPMG, 2025).

3. ⚕️ **Enhanced Trust**  
   Transparent AI increases clinician adoption, reduces litigation risk, and enables **shared decision-making**.

---

## # Business Recommendations

- ✅ **Deploy** this system in hospitals and diagnostics centers with EHR integration.
- 📊 **Use dashboards** in tumor board reviews to explain diagnostic rationale.
- 🧠 **Segment patients** using SHAP clusters to personalize diagnostics and follow-up.
- 🔄 **Track model drift** by continuously monitoring prediction quality in Power BI.

---

## # Project Links

- 📄 [Dashboard PDF Preview](https://github.com/SweetySeelam2/Breast-Cancer-Risk-Predictor/blob/main/Breast%20Cancer%20Prediction.pdf)
- 🌐 [Live Streamlit App](https://livedata-breastcancer-predictor.streamlit.app/)
- 📦 [GitHub Repo](https://github.com/SweetySeelam2/Breast-Cancer-Risk-Predictor)

---

## # Project Storytelling

> "**Breast Cancer Risk Prediction with Explainable AI: From Raw Data to Real Decisions**"

This project demonstrates how **interpretable machine learning** can drive real-world impact. Combining **Logistic Regression** with **SHAP explanations** and visual analytics, it shows how AI can assist clinicians — not just with predictions, but with **trustworthy, data-backed reasoning**.

---

## # References

- UCI Dataset: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)  
- Lundberg & Lee, SHAP Paper: https://arxiv.org/abs/1705.07874  
- KPMG Healthcare AI Insights (2025): https://home.kpmg/xx/en/home/insights/2025/healthcare-innovation.html

---

## 👩‍💼 About the Author    

**Sweety Seelam** | Business Analyst | Aspiring Data Scientist | Passionate about building end-to-end ML solutions for real-world problems                                                                                                      
                                                                                                                                           
Email: sweetyseelam2@gmail.com                                                   

🔗 **Profile Links**                                                                                                                                                                       
[Portfolio Website](https://sweetyseelam2.github.io/SweetySeelam.github.io/)                                                         
[LinkedIn](https://www.linkedin.com/in/sweetyrao670/)                                                                   
[GitHub](https://github.com/SweetySeelam2)                                                             
[Medium](https://medium.com/@sweetyseelam)

---

## 🔐 Proprietary & All Rights Reserved
© 2025 Sweety Seelam. All rights reserved.

This project, including its source code, trained models, datasets (where applicable), visuals, and dashboard assets, is protected under copyright and made available for educational and demonstrative purposes only.

Unauthorized commercial use, redistribution, or duplication of any part of this project is strictly prohibited.
