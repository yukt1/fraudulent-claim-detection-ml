\# Fraudulent Claim Detection — ML Classification



This project builds a \*\*fraud detection pipeline\*\* for insurance claims using supervised machine learning. It compares \*\*Logistic Regression vs Random Forest\*\*, evaluates model performance, and surfaces fraud-driving indicators to support early investigation and loss prevention.



---



\## Business Objective



Insurance fraud increases claim costs and operational workload. The goal is to:

\- Predict whether a claim is \*\*fraudulent\*\*

\- Identify \*\*high-risk claims\*\* for early manual review

\- Reduce financial loss and improve investigation efficiency



---



\## Key Results 



\### Logistic Regression (Training)

\- \*\*Training Accuracy:\*\* ~0.83



\### Random Forest

\- \*\*Training Accuracy:\*\* 1.00 (suggests overfitting risk)

\- \*\*Mean Cross-Validation Accuracy:\*\* ~0.9467



\### Validation Performance

\- \*\*Random Forest Validation Accuracy:\*\* ~0.7413

\- \*\*Validation F1 Score:\*\* ~0.384



> Note: Fraud datasets are often imbalanced; therefore \*\*F1 score\*\* is an important metric alongside accuracy.



---



\## What This Project Demonstrates



\- End-to-end classification workflow: EDA → preprocessing → modeling → evaluation

\- Model comparison: \*\*Logistic Regression vs Random Forest\*\*

\- Performance validation using:

&nbsp; - accuracy

&nbsp; - confusion matrix

&nbsp; - F1 score

&nbsp; - cross-validation

\- Practical fraud analytics framing and interpretation



---



\## Tech Stack



\- Python, Jupyter Notebook  

\- Libraries:

&nbsp; - pandas, numpy

&nbsp; - matplotlib, seaborn

&nbsp; - scikit-learn



---



\## Project Structure



```text

fraudulent-claim-detection-ml/

├─ notebooks/

│  └─ Fraudulent\_Claim\_Detection.ipynb

├─ data/

├─ README.md

├─ requirements.txt

└─ .gitignore



How to Run

Install dependencies:





pip install -r requirements.txt

Place dataset (or your CSV) in data/



Run the notebook:





jupyter notebook notebooks/Fraudulent\_Claim\_Detection.ipynb



