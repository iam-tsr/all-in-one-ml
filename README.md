# All-in-One Machine Learning

A comprehensive machine learning learning repository covering core algorithms, mathematical foundations, and real-world case studies — from linear regression to neural networks and beyond.

---

## Supervised Learning

Each algorithm includes an **explanation notebook** (theory & math) and a **practice notebook** (implementation with real data).

| Algorithm | Description | Key Concepts |
|-----------|-------------|--------------|
| [Linear Regression](supervised-learning/linear-regression/) | Model relationships between variables | OLS, SSE minimization, parameter estimation |
| [Logistic Regression](supervised-learning/logistic-regression/) | Probabilistic binary classification | Sigmoid function, weight updates, decision boundary |
| [Decision Tree](supervised-learning/decision-tree/) | Tree-based classification & regression | Entropy, information gain, tree visualization |
| [K-Nearest Neighbors](supervised-learning/knn/) | Instance-based lazy learning | Euclidean distance, k-value tuning, overfitting vs underfitting |
| [Support Vector Machine](supervised-learning/svm/) | Maximum margin classifier | Hyperplane, support vectors, kernel trick (Linear, Poly, RBF) |
| [Naive Bayes](supervised-learning/naive-bayes-classifier/) | Probabilistic classifier via Bayes' Theorem | Posterior probability, feature independence assumption |
| [Linear Discriminant Analysis](supervised-learning/lda/) | Dimensionality reduction + classification | Fisher's criterion, scatter matrices, eigenvalue decomposition |
| [Feedforward Neural Network](supervised-learning/ffn/) | Intro to neural networks | Forward pass, activation functions, backpropagation |

### Resampling Techniques

| Technique | Description |
|-----------|-------------|
| [K-Fold Cross-Validation](supervised-learning/resampling-techniques/k-folds/) | Split data into k subsets for robust model evaluation |
| [Leave-One-Out (LOO)](supervised-learning/resampling-techniques/loo/) | Extreme k-fold where each sample is a test set once |

---

## Unsupervised Learning

| Algorithm | Description | Key Concepts |
|-----------|-------------|--------------|
| [K-Means Clustering](unsupervised-learning/k-means/) | Centroid-based clustering | Centroid updates, convergence, feature scaling, elbow method |
| [PCA](unsupervised-learning/PCA/) | Dimensionality reduction | Variance maximization, principal components, feature importance |
| [DBSCAN](unsupervised-learning/DBSCAN/) | Density-based clustering | Arbitrary cluster shapes, noise handling, eps/min_samples tuning |
| [Hierarchical Clustering](unsupervised-learning/hierarchical-clustering/) | Tree-based cluster hierarchy | Dendrograms, Ward linkage, distance thresholds |

---

## Case Studies

Real-world projects applying ML techniques to practical problems.

| Project | Problem Type | Description |
|---------|-------------|-------------|
| [Bank Customer Turnover](case-studies/bank-turnover/) | Classification | Predict bank customer churn |
| [House Price Prediction](case-studies/house_price/) | Regression | Predict property prices from features |
| [Iris Flower Classification](case-studies/iris-flower/) | Classification | Classic multi-class species classification |
| [Mental Health Prediction](case-studies/mental-health/) | Classification | Predict mental health conditions (Kaggle Playground S4E11) |
| [Fraud Detection](case-studies/fraud-detection/) | Classification | Detect fraudulent transactions (imbalanced data) |
| [Telco Customer Churn](case-studies/telco-custm-churn/) | Classification | Predict telecom customer churn |
| [Titanic Survival](case-studies/titanic/) | Classification | Predict passenger survival (Kaggle competition) |
| [Calorie Expenditure](case-studies/predict-calorie-expenditure/) | Regression | Predict calorie burn from biometric data |
| [Subscription Service Churn](case-studies/subsciption-service/) | Classification | Predict SaaS/subscription churn |
| [Spark Data Manipulation](case-studies/spark/) | Big Data | Large-scale data processing with Apache Spark |

---

## Datasets

The `datasets/` directory contains 47 files used across notebooks, including:

- **Classification**: Iris, Titanic, Telco Churn, Diabetes, Loan Prediction, Wine Quality
- **Regression**: House Prices, Auto MPG, Insurance, Taxi Fare, Concrete
- **Clustering**: Mall Customers, Cardio Fitness
- **Other**: Hotel Bookings, HR Analytics, Google Store, World Happiness Report

---

## Suggested Learning Path

1. **Foundations** — Start with Linear Regression and Logistic Regression
2. **Core Classifiers** — Decision Tree → KNN → SVM → Naive Bayes
3. **Dimensionality Reduction** — LDA and PCA
4. **Model Evaluation** — K-Fold and LOO cross-validation
5. **Clustering** — K-Means → DBSCAN → Hierarchical Clustering
6. **Neural Networks** — Feedforward Neural Networks
7. **Apply** — Work through case studies to solidify concepts

---

## Tech Stack

- **Python 3** with Jupyter Notebooks
- **Core Libraries**: NumPy, Pandas, Matplotlib, Seaborn
- **ML Frameworks**: scikit-learn
- **Big Data**: PySpark (Spark case study)

---

*~TSR*