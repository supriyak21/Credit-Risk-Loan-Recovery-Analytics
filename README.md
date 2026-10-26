# Credit Risk Modeling & Loan Recovery Analytics

### Overview
End-to-end credit risk analysis of **2.26M+ historical loans**, combining portfolio analytics, recovery assessment, and predictive modeling to evaluate charge-off risk and support risk-based portfolio monitoring.

### Methodology
- Analyzed **262K+ charged-off loans**, recovery rates, and portfolio risk patterns.
- Built a **Logistic Regression pipeline** with feature preprocessing, missing-value handling, and outlier treatment.
- Applied **chronological train, validation, and test splits** to assess model performance over time.
- Evaluated risk discrimination, decile-level risk concentration, and probability calibration.

### Key Results
- **ROC-AUC: 0.679** on 282,853 out-of-time test loans.
- **6.83× risk separation** between highest- and lowest-risk deciles.
- **20.7% of charge-offs** concentrated in the highest-risk 10% of loans.
- Improved Brier score from **0.121513 to 0.121378** through post-hoc recalibration.

### Tech Stack
Python | pandas | scikit-learn | Statistical Analysis | Predictive Modeling | Model Evaluation

### Business Application
Supports credit-risk segmentation, portfolio monitoring, and prioritization of higher-risk accounts. Historical analysis only; further validation is required for operational lending decisions.

**Dataset:** Historical LendingClub loan records.
