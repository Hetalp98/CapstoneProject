# CapstoneProject
Predicting Autism Spectrum Disorder (ASD) in Toddlers

📌 Overview
This capstone project aims to build a predictive model using behavioral and demographic data to identify Autism Spectrum Disorder (ASD) traits in toddlers early, enabling timely interventions.

🎯 Problem Statement
ASD diagnosis is often delayed, which limits access to early support and intervention. Our goal was to create a machine learning-based preliminary screening tool to help identify at-risk toddlers sooner.

📊 Dataset
Source: Department of Digital Technology, Manukau Institute of Technology, New Zealand  
Number of records: 1,054  
Features:
Behavioral (Q-Chat-10): A1–A10  
Demographic: Age in months, Sex, Ethnicity, Jaundice history, Family ASD history, Test completion details  
Target Variable: ASD Traits (Yes/No) 

*Note: Dataset is not uploaded due to licensing. Please refer to the original source for access.*

🛠 Methodology
1. Data Preprocessing
   - One-hot encoding for categorical variables
   - Standardization for numerical features
   - SMOTE for class balancing
2. Models Evaluated
   - Logistic Regression (baseline)
   - Decision Tree
   - Random Forest
3. Evaluation Metrics
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - AUC-ROC

📈 Results
| Model              | Accuracy | Precision | Recall | F1 Score | AUC   |
|--------------------|----------|-----------|--------|----------|-------|
| Logistic Regression| 96.7%    | 96.3%     | 99.3%  | 97.8%    | 0.981 |
| Decision Tree      | 99.5%    | 99.3%     | 100%   | 99.6%    | 1.000 |
| Random Forest      | 99.5%    | 99.3%     | 100%   | 99.6%    | 1.000 |

Best Performer: Random Forest — Perfect recall with high accuracy and generalization.

💡 Applications
- Healthcare: Early ASD screening for pediatricians and general practitioners.
- Education: Tools for early childhood educators and school counselors.
- Digital Platforms: Parent-led screening apps for home use.
- Clinical Support: Prioritizing patients in clinics with limited ASD specialists.

 🚀 Future Work
- Apply cross-validation and hyperparameter tuning for robustness.
- Integrate SHAP/LIME for model interpretability.
- Test on diverse populations for generalizability.
- Explore multimodal data (e.g., video/audio cues).
