# Brain Cancer Disease Detection using ensemble methods

## Dataset

(Synthetic data)[https://data.world/seekersoftec/risk-of-brain-tumor]
This data was crated from (This one)[https://archive.ics.uci.edu/ml/machine-learning-databases/00383/risk_factors_cervical_cancer.csv]

## Proposed Methodology

- SVM with different kernels such as RBF, Polynomial, Sigmoid and Linear, MLP, Naive Bayes

- 4 filter FS methods such as info. gain, gain ratio, reliefF and Chi square

- 1 embedded FS method such as RFE-SVM(RBF)

- Combination Method: Majority Voting and other embedded Feature Selection methods such as RFE-SVM(RBF), MIFEB, PRIFEB
- Base Classifiers: SVM[with different kernel functions], MLP, Naive Bayes, KNN, Logistic Regression

- Ensemble methods: Stacking[with Logistic Regression as Meta Model], Bagging and Boosting
