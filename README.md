# 🍊 Fruit Classification (Orange vs Grapefruit)

A binary classification project using an Artificial Neural Network (ANN) to distinguish between oranges and grapefruits based on physical and color-based features.

---

## 📌 Overview
This project leverages a tabular dataset containing fruit properties such as diameter, weight, and RGB color values. The goal is to accurately classify each sample as either an orange or a grapefruit using a deep learning model.

---

## 🛠️ Workflow Summary

### 🔄 Data Preprocessing
- Categorical target labels (fruit names) were encoded numerically using a label encoder.
- All input features were scaled to ensure balanced training and faster convergence.

### 🧠 Model Architecture
- A Sequential ANN was constructed with three hidden layers using ReLU activations.
- The final output layer used a sigmoid activation to produce probabilities for binary classification.

### ⚙️ Training & Optimization
- The model was compiled using the Adam optimizer with a learning rate of 0.001.
- It was trained for 100 epochs using binary cross-entropy as the loss function and accuracy as the evaluation metric.

### 📈 Evaluation
- Model predictions were thresholded at 0.5 to obtain class labels.
- Performance was assessed using precision, recall, f1-score, and accuracy, all provided in a detailed classification report.

---

## ✅ Results
Achieved **98% accuracy** in correctly identifying oranges and grapefruits, demonstrating strong performance on a well-preprocessed and balanced tabular dataset.

---

## 🙌 Author
**Hemlalit Mali**  
[GitHub](https://github.com/hemlalit) $|$ [LinkedIn](https://www.linkedin.com/in/hemlalit)

---

_“Train to predict, but always test to learn.”_
