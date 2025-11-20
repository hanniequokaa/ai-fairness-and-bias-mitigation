**AI Fairness and Bias Mitigation Assignment**
**Overview**

This repository contains the AI Ethics assignment for the theme “Designing Responsible and Fair AI Systems”. The assignment focuses on auditing AI systems for bias, analyzing case studies, and applying fairness mitigation strategies using IBM’s AI Fairness 360 toolkit.

**Contents**


AI-FAIRNESS-ML.ipynb – Jupyter Notebook performing a fairness audit on the COMPAS recidivism dataset, including data preprocessing, bias metrics, logistic regression modeling, and mitigation techniques.

compas-scores-two-years.csv – COMPAS dataset used for bias analysis.

AI Ethics Assignment.pdf – Written report including theoretical questions, case study analysis, audit report, ethical reflection, and healthcare policy proposal.

AI Ethics Assignment.docx – Word version of the report.

**Tools & Libraries**

Python 3.x

Pandas, NumPy, Matplotlib

Scikit-learn

AI Fairness 360
 (IBM toolkit for fairness auditing and mitigation)

**Assignment Structure**

Theoretical Understanding

Algorithmic bias, transparency, explainability, GDPR impacts

Ethical principles: Justice, Non-maleficence, Autonomy, Sustainability

Case Study Analysis

Biased Hiring Tool (Amazon)

Facial Recognition in Policing

Practical Audit

COMPAS dataset fairness audit using AIF360

Metrics computed: Statistical Parity Difference, Disparate Impact Ratio, False Positive/Negative Rate Differences

Bias mitigation applied: Reweighing

Ethical Reflection

Future AI project considerations for ethical design

Bonus

Ethical AI guidelines for healthcare systems

**Notes**

The notebook loads the COMPAS dataset and performs all computations locally.

The dataset is included in the repo for reproducibility.

Temporary files and Word autosaves (e.g., ~$*.docx) have been excluded via .gitignore.

**Author

Robert Moraa – AI Ethics Assignment, PLP Academy**
# ai-fairness-and-bias-mitigation