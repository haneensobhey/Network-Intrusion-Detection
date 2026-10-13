# 🛡️ Network Intrusion Detection Using Machine Learning

## 📌 Overview

This project focuses on detecting network intrusions using Machine Learning classification techniques. It analyzes network traffic features to classify connections into different categories and identify potentially malicious activity.

The project covers data exploration, preprocessing, feature scaling, feature selection, model training, and performance evaluation.

## 🎯 Objectives

- Analyze network traffic data.
- Prepare and preprocess features for Machine Learning.
- Encode categorical variables.
- Apply feature scaling where appropriate.
- Perform feature selection.
- Train a classification model.
- Evaluate performance using multiple classification metrics.

## 📂 Dataset

The project uses network traffic data from the following files:

- `Train_data.csv`
- `Test_data.csv`

The dataset includes features such as `duration`, `protocol_type`, `service`, `flag`, `src_bytes`, and `dst_bytes`.

**Target variable:** `class`

## ⚙️ Project Workflow

1. Data Loading and Exploration
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Categorical Feature Encoding
5. Feature Scaling
6. Feature Selection
7. Model Training
8. Model Evaluation

## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## 📊 Model Evaluation

The model achieved the following results on 5,039 evaluated samples:

| Metric | Score |
|---|---:|
| Accuracy | 99.78% |
| Macro Precision | 99.78% |
| Macro Recall | 99.78% |
| Macro F1-score | 99.78% |
| Weighted F1-score | 99.78% |

The classification report also showed strong precision, recall, and F1-score for both target classes.

*Note: The reported scores reflect the evaluation performed in this project. Class labels should be mapped to their actual categories according to the dataset.*

## 📁 Repository Structure

```text
Network-Intrusion-Detection/
├── README.md
└── Network_Intrusion_Detection.ipynb
```

## 🚀 Future Improvements

- Compare multiple classification algorithms.
- Analyze feature importance.
- Evaluate generalization on independent test data.
- Investigate false positives and false negatives.

## 👩‍💻 Author

**Haneen Sobhey**

Computer Science Student | Machine Learning Enthusiast

[GitHub Profile](https://github.com/haneensobhey)

---

*This project demonstrates the application of Machine Learning techniques to network security.*
