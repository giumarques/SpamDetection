# Spam Detection with Random Forest

This project demonstrates how to build a machine learning model to detect spam emails using the [Spambase dataset](https://www.kaggle.com/datasets/somesh24/spambase). The model is trained using a Random Forest classifier and evaluated with ROC curve and AUC metrics.

## 📌 Project Goals

- Understand and explore the Spambase dataset.
- Preprocess the data to prepare it for machine learning.
- Train a classification model to identify spam emails.
- Evaluate the model's performance using appropriate metrics.

## 📊 Dataset

The dataset contains various statistical attributes of email content, such as the frequency of certain words and characters, which are used to classify emails as spam (`1`) or not spam (`0`).

You can download the dataset directly from Kaggle:  
👉 https://www.kaggle.com/datasets/somesh24/spambase

## 🧠 Machine Learning Model

- **Algorithm**: Random Forest Classifier  
- **Target variable**: `class` (1 = spam, 0 = non-spam)  
- **Evaluation**: ROC Curve and AUC

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spam-detection-rf.git
   cd spam-detection-rf

## 🧪 Results

The Random Forest classifier achieved an AUC score of **0.96**, demonstrating excellent ability to distinguish between spam and legitimate emails. The ROC curve showed a strong separation between the two classes, confirming the model’s reliability.

## 📝 Conclusion

The Random Forest classifier performed well in classifying spam and non-spam emails, achieving high AUC scores and demonstrating the effectiveness of the model in this task. The ROC curve further validated the model's robustness.

