# Types of Machine Learning Algorithms

---

# 1. Supervised Learning

## Definition:
Learning from labeled data (input + correct output).

Example:
X → Y  
House features → Price  

---

## 1.1 Classification

Predicts categories.

### Examples:
- Spam / Not Spam
- Disease / No Disease
- Fraud / Not Fraud

### Algorithms:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- Neural Networks

---

## 1.2 Regression

Predicts continuous values.

### Examples:
- House price prediction
- Salary prediction
- Temperature forecasting

### Algorithms:
- Linear Regression
- Ridge/Lasso
- Decision Tree Regressor
- Random Forest Regressor
- SVR

---

# 2. Unsupervised Learning

## Definition:
Learning from unlabeled data.

Example:
Customer purchase data → Find groups

---

## 2.1 Clustering

Grouping similar data points.

### Algorithms:
- K-Means
- Hierarchical Clustering
- DBSCAN
- Gaussian Mixture Models

---

## 2.2 Dimensionality Reduction

Reducing features while keeping information.

### Algorithms:
- PCA
- t-SNE
- UMAP

---

# 3. Reinforcement Learning (RL)

## Definition:
Learning by interacting with environment using rewards and penalties.

Agent → Action → Reward → Learn

### Examples:
- Game playing (AlphaGo)
- Robotics
- Self-driving cars

### Algorithms:
- Q-Learning
- SARSA
- Deep Q Networks (DQN)
- Policy Gradient
- PPO

---

# Instance-Based vs Model-Based Learning

## 1. Instance-Based Learning

- Stores training examples
- Makes prediction using similarity
- Lazy learning

### Example:
K-Nearest Neighbors (KNN)

Prediction:
Look at closest data points → Vote

Pros:
- Simple
- No training phase

Cons:
- Slow at prediction
- Memory heavy

---

## 2. Model-Based Learning

- Learns a mathematical function
- Generalizes from data

### Example:
Linear Regression

Learns:
Y = mx + b

Pros:
- Fast prediction
- Generalizes well

Cons:
- Assumes model structure

---

# Geometry in Machine Learning

## 1. Equation of a Line (2D)

Y = mX + b

Where:
- m = slope
- b = intercept

Separates 2 classes in 2D space.

---

## 2. Equation of a Plane (3D)

aX + bY + cZ + d = 0

Separates data in 3D space.

---

## 3. Hyperplane (n-dimensions)

w1x1 + w2x2 + ... + wnxn + b = 0

Or:

w^T x + b = 0

Used in:
- SVM
- Logistic Regression
- Neural Networks

Hyperplane separates classes in higher dimensions.

---

# Visualization Suggestion

To visualize:

- 2D Line → Plot using matplotlib
- 3D Plane → 3D scatter + surface plot
- Hyperplane → Conceptual diagram (cannot directly visualize beyond 3D)

Suggested tools:
- Python (matplotlib, plotly)
- GeoGebra
- Desmos
