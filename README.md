🍄 Mushroom Edibility Classification

Machine Learning Project | Supervised & Unsupervised Learning

📌 Project Overview

This project focuses on classifying mushrooms as edible or poisonous using machine learning techniques.

Using the Secondary Mushroom Dataset, the project explores different classification algorithms to predict mushroom edibility based on physical characteristics such as cap shape, cap color, gill characteristics, and other features.

The project also applies unsupervised learning to explore patterns and groupings within the dataset.

The primary goal is to compare different machine learning models and understand how effectively they can distinguish between edible and poisonous mushrooms.

---

🎯 Objectives

- Classify mushrooms as edible or poisonous based on their characteristics.
- Apply and compare multiple supervised machine learning algorithms.
- Explore patterns in mushroom data using unsupervised learning.
- Perform data preprocessing and feature engineering.
- Evaluate model performance using appropriate metrics.
- Understand the strengths and limitations of different machine learning approaches.

---

📊 Dataset

Dataset: Secondary Mushroom Dataset

The dataset contains information about mushrooms, including their physical characteristics and edibility.

Property| Description
Number of instances| 61,069
Number of species| 173
Target variable| "class"
Edible class| "e"
Poisonous class| "p"
Feature type| Primarily categorical

Target Variable

The target variable is "class", which represents mushroom edibility:

- "e" — Edible
- "p" — Poisonous

---

🛠️ Technologies Used

- Python — Programming language
- Pandas — Data manipulation and analysis
- NumPy — Numerical computing
- Scikit-learn — Machine learning algorithms and preprocessing
- Matplotlib — Data visualization
- Seaborn — Statistical data visualization
- Jupyter Notebook — Interactive development and experimentation

---

🤖 Machine Learning Models

This project explores the following algorithms:

1. K-Nearest Neighbors (KNN)

A supervised learning algorithm that classifies a mushroom based on the classes of its nearest data points.

2. Logistic Regression

A supervised classification algorithm that estimates the probability of a mushroom belonging to a particular class.

3. Neural Network

A supervised learning model that learns complex patterns in mushroom characteristics to predict edibility.

4. K-Means Clustering

An unsupervised learning algorithm used to identify patterns and groupings in mushroom data without relying on class labels during clustering.

---

⚙️ Data Preprocessing

The dataset undergoes several preprocessing steps before model training.

1. Handling Missing Values

- Certain features containing substantial missing information are removed.
- Missing values in selected categorical features are replaced with a ""missing"" category.

2. Feature Selection

The following features are removed during preprocessing:

- "veil-type"
- "veil-color"
- "spore-print-color"
- "stem-root"
- "stem-surface"

3. Categorical Encoding

Categorical features are converted into numerical representations using One-Hot Encoding.

The resulting feature set contains 81 encoded features.

4. Feature Scaling

"StandardScaler" is applied to prepare the data for algorithms sensitive to feature scales, including:

- K-Nearest Neighbors
- Logistic Regression
- Neural Network

5. Train-Test Split

The dataset is divided into training and testing sets using an 80:20 split.

Stratified sampling is used to preserve the class distribution across the two sets.

Cross-validation is also used to assess model performance.

---

📈 Model Evaluation

The models can be evaluated using the following metrics:

- Accuracy: Proportion of correctly classified samples.
- Precision: Proportion of predicted positive samples that are actually positive.
- Recall: Proportion of actual positive samples correctly identified.
- F1-Score: Harmonic mean of precision and recall.
- Confusion Matrix: Shows correct and incorrect predictions for each class.

For mushroom classification, recall for the poisonous class is particularly important because failing to identify a poisonous mushroom can have serious consequences.

Note: This project is for educational purposes and should not be used to determine whether a real mushroom is safe to eat.

---

📂 Project Structure

Mushroom-Classification/
│
├── dataset/
│   └── secondary_data.csv
│
├── notebooks/
│   └── mushroom_classification.ipynb
│
├── README.md
└── requirements.txt

The structure above is a suggested layout and can be adjusted to match the actual repository.

---

🚀 Getting Started

Prerequisites

Make sure Python is installed on your system.

1. Clone the Repository

git clone <your-repository-url>

2. Navigate to the Project Directory

cd Mushroom-Classification

3. Install Dependencies

pip install -r requirements.txt

4. Run the Project

Open the Jupyter Notebook:

jupyter notebook

Then open the mushroom classification notebook and run the cells sequentially.

---

🔍 Key Learning Outcomes

Through this project, we explore:

- Data cleaning and preprocessing techniques.
- Handling missing values in categorical datasets.
- Encoding categorical variables for machine learning.
- Training and comparing supervised learning algorithms.
- Applying unsupervised learning to discover patterns.
- Evaluating classification performance using multiple metrics.
- Understanding the importance of reliable classification in safety-sensitive applications.

---

⚠️ Disclaimer

This project is intended for academic and educational purposes only.

Machine learning predictions are not a reliable substitute for expert mushroom identification. Never consume a mushroom based on this project's predictions.

---

👩‍💻 Contributors

Project: Mushroom Edibility Classification

Course: Machine Learning

Author: Tabassum

---

⭐ If you find this project interesting, consider giving the repository a star!
