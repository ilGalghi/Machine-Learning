# Machine Learning Exam Exercise Analysis

Based on the analysis of 29 exam files, here is the breakdown of exercise types, their frequency, and where they appear. Made in Python

## Most Common Exercise Types

### 1. Support Vector Machines (SVM)
**Frequency:** 20 exams
**Description:** Questions typically involve:
- Describing the maximization of the margin.
- Soft margins and slack variables.
- Kernel functions.
- Solving for small datasets or drawing boundaries.
**Appears in:** `exam_20181220`, `exam_2018_01`, `exam_2018_02`, `exam_201901-A`, `exam_201901-B`, `exam_201902-A`, `exam_201902-B`, `exam_20191015`, `exam_20191104`, `exam_20210119`, `exam_20210622`, `exam_20231218`, `exam_20240119`, `exam_20240726`, `exam_20241216`, `exam_20250130`, `exam_20250917`, `exam_20251217`, `examtest1`

### 2. Neural Networks (MLP & Backprop)
**Frequency:** 16 exams
**Description:** Questions focus on:
- Feedforward architecture and activation functions.
- Backpropagation algorithm steps.
- Stochastic Gradient Descent (SGD) details.
- Designing a network for a specific regression/classification problem.
**Appears in:** `exam_20181220`, `exam_2018_02`, `exam_2018_03`, `exam_201901-A`, `exam_201901-B`, `exam_20191216_erasmus`, `exam_20210119`, `exam_20231218`, `exam_20240119`, `exam_20240726`, `exam_20250917`, `examtest2`

### 3. Bayesian Learning
**Frequency:** 12 exams
**Description:** Common topics:
- Bayes Theorem application.
- MAP (Maximum A Posteriori) vs ML (Maximum Likelihood) hypotheses.
- Naive Bayes Classifier.
- Bayes Optimal Classifier.
**Appears in:** `exam_2018_01`, `exam_2018_03`, `exam_201901-A`, `exam_201901-B`, `exam_20191015`, `exam_20191216_erasmus`, `exam_20231218`, `exam_20240119`, `exam_20241216`, `exam_20250917`, `exam_20251022`, `exam_20251217`

### 4. Decision Trees
**Frequency:** 10 exams
**Description:** Exercises often ask to:
- Classify a sample given a tree.
- Calculate Entropy or Information Gain.
- Draw a decision tree for a simple dataset.
**Appears in:** `exam_2018_02`, `exam_2018_03`, `exam_201901-A`, `exam_201901-B`, `exam_20191104`, `exam_20191216_erasmus`, `exam_20231218`, `exam_20250130`, `exam_20251022`, `examtest1`

### 5. Evaluation Metrics
**Frequency:** 10 exams
**Description:** Focus on performance measurement:
- Confusion Matrix definition and calculation.
- Accuracy, Precision, Recall, F1 Score.
- ROC curves.
- Overfitting definitions.
**Appears in:** `exam_201902-A`, `exam_201902-B`, `exam_20191104`, `exam_20210119`, `exam_20210622`, `exam_20240119`, `exam_20240726`, `exam_20241216`, `exam_20250917`, `examtest1`

### 6. K-Nearest Neighbors (K-NN)
**Frequency:** 8 exams
**Description:**
- Algorithm description.
- Classifying a point given a 2D dataset.
- Choice of K.
**Appears in:** `exam_20181220`, `exam_2018_03`, `exam_201902-A`, `exam_201902-B`, `exam_20191015`, `exam_20191104`, `exam_20250917`, `examtest1`

### 7. CNNs (Convolutional Neural Networks)
**Frequency:** 7 exams
**Description:**
- Calculating output dimensions and parameter counts for specific layers (Conv, Pool).
- describing operations (Stride, Padding).
**Appears in:** `exam_2018_01`, `exam_201902-A`, `exam_201902-B`, `exam_20210622`, `exam_20240726`, `exam_20250130`, `exam_20251022`

### 8. Clustering (K-Means)
**Frequency:** 7 exams
**Description:**
- Unsupervised learning definitions.
- K-Means algorithm steps and termination conditions.
- Simulating K-Means on small 2D datasets.
**Appears in:** `exam_20181220`, `exam_2018_03`, `exam_20191216_erasmus`, `exam_20210622`, `exam_20240119`, `exam_20250130`, `examtest2`

### 9. Linear Models (Regression/Classification)
**Frequency:** 7 exams
**Description:**
- Linear Regression and Perceptron.
- Outliers effect.
- Linearly separable data.
**Appears in:** `exam_2018_01`, `exam_2018_03`, `exam_201901-A`, `exam_201901-B`, `exam_20191104`, `exam_20250130`, `examtest1`

### 10. Ensemble Methods
**Frequency:** 6 exams
**Description:**
- Bagging and Boosting.
- AdaBoost algorithm error function.
**Appears in:** `exam_20181220`, `exam_2018_02`, `exam_20191015`, `exam_20250917`, `exam_20251217`, `examtest2`

### 11. Markov Models & Reinforcement Learning
**Frequency:** 6 exams
**Description:**
- Markov Property.
- Difference between MDP and HMM.
- Graphical models.
**Appears in:** `exam_2018_01`, `exam_201902-A`, `exam_201902-B`, `exam_20240726`, `examtest2`

### 12. Dimensionality Reduction (PCA)
**Frequency:** 3 exams
**Description:**
- Intrinsic dimensionality.
- Principal Component Analysis steps.
**Appears in:** `exam_2018_01`, `exam_20210119`, `exam_20210622`

### Other / General Theory
**Frequency:** ~19 exams
**Description:**
- General definitions (Supervised vs Unsupervised).
- General hypothesis consistency checks.
- Gaussian Mixture Models (GMM) (`exam_201902-A`, `exam_201902-B`, `exam_20240726`).
- Autoencoders (Architecture and purpose) (`exam_20181220`, `exam_20191216_erasmus`, `examtest2`).



# Timeline

Based on the analysis of 29 exam files, categorized by topic and temporal trends.
**Total Exams Analyzed**: 29
**Total Exercises Identified**: 119

## temporal Trends: Recent (2023-Present) vs Older (Pre-2023)

### Trending UP 📈
*   **Bayesian Learning**: Has seen a significant increase in frequency in recent exams.
*   **SVM**: Remains a staple, consistently appearing with high frequency.

### Stable / Recurring ↔️
*   **Neural Networks**: Consistently popular, though slightly less dominant than in older exams.
*   **Evaluation Metrics**: Frequently asked as sub-questions (Precision, Recall, etc.).
*   **Clustering (K-Means)**: Appears steadily.

### Less Frequent Recently 📉
*   **K-NN**: Appears less often in recent exams compared to the past.
*   **Linear Models**: Direct questions on simple linear regression/perceptron are fewer, often replaced by more complex models.

---

## Detailed Exercise Categories

### 1. Support Vector Machines (SVM)
**Total Count:** 19
**Recent Frequency (Post-2023):** 7 (High)
**Typical Questions:**
- Maximize margin, soft margins (slack variables), kernel trick.
- **Example**: "Describe the principle of soft margins... draw a dataset..."
- **Files**: `exam_2018_01`, `exam_20210622`, `exam_20240119`, `exam_20250130`, `exam_20250917` ...

### 2. Neural Networks (MLP & Backprop)
**Total Count:** 18
**Recent Frequency (Post-2023):** 5 (Med-High)
**Typical Questions:**
- Architectures (Hidden units, Activation functions).
- Backpropagation algorithm steps.
- Stochastic Gradient Descent (SGD).
- **Files**: `exam_20181220`, `exam_20231218`, `exam_20240726`, `exam_20250917` ...

### 3. Bayesian Learning
**Total Count:** 12
**Recent Frequency (Post-2023):** 6 (High - Trending Up)
**Typical Questions:**
- MAP vs ML hypotheses.
- Bayes Optimal Classifier.
- Naive Bayes Classifier definitions.
- **Files**: `exam_2018_01`, `exam_20231218`, `exam_20241216`, `exam_20251022`, `exam_20251217` ...

### 4. Decision Trees
**Total Count:** 9
**Recent Frequency (Post-2023):** 3 (Medium)
**Typical Questions:**
- Entropy/Information Gain calculations.
- Classify samples using a given tree.
- **Files**: `exam_20191104`, `exam_20250130`, `exam_20251022` ...

### 5. Evaluation Metrics
**Total Count:** 9
**Recent Frequency (Post-2023):** 4 (Medium)
**Typical Questions:**
- Confusion Matrix, Accuracy, Precision, Recall.
- Overfitting definitions.
- **Files**: `exam_20240119`, `exam_20241216`, `exam_20250917` ...

### 6. Clustering (K-Means & GMM)
**Total Count:** 9
**Recent Frequency (Post-2023):** 3 (Medium)
**Typical Questions:**
- K-Means steps and termination.
- Gaussian Mixture Models (GMM) definitions.
- **Files**: `exam_20240119`, `exam_20250130` ...

### 7. CNNs (Convolutional Neural Networks)
**Total Count:** 7
**Recent Frequency (Post-2023):** 3 (Medium)
**Typical Questions:**
- Parameter counting, output dimensions (stride/padding).
- **Files**: `exam_20210622`, `exam_20240726`, `exam_20250130` ...

### 8. Ensemble Methods
**Total Count:** 5
**Recent Frequency (Post-2023):** 2 (Low-Medium)
**Typical Questions:**
- Bagging vs Boosting.
- AdaBoost error function.
- **Files**: `exam_20191015`, `exam_20250917`, `exam_20251217` ...

### 9. Other / General Theory
**Total Count:** 10+
**Recent Frequency (Post-2023):** 5
**Sub-Categories in "Other":**
*   **General Regression/Classification Theory**: Questions asking to "Describe a linear model for this problem" or "Is this dataset linearly separable?" without specifying a named algorithm.
*   **Generative Models**: Questions about "Probabilistic generative models" (overlap with Bayesian).
*   **Instructions**: Some "Exercises" detected were just exam instructions.

---

## Exercise Inventory by Period

### Recent Exams (Examples)
*   `exam_20251217`: Bayesian, SVM, Ensemble.
*   `exam_20250917`: SVM, Neural Networks, K-NN, Evaluation Metrics.
*   `exam_20250130`: SVM, Decision Trees, CNNs, Linear Models.
*   `exam_20241216`: Bayesian, Evaluation Metrics.

### Older Exams (Examples)
*   `exam_2018_01`: CNN, Bayesian, SVM, Linear Models, Instructions.
*   `exam_201901-A`: Neural Networks, Decision Trees, SVM, Linear Models.
