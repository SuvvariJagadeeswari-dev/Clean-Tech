# 🧼 CleanTech: Transforming Waste Management with Transfer Learning

## 📝 Overview

This project aims to classify images of municipal waste into three categories:

- ♻️ **Recyclable**
- 🌱 **Biodegradable**
- 🚮 **Trash**

Built using a **pre-trained VGG16** deep learning model and deployed through a **Flask web application**, this tool helps automate waste segregation to support smarter waste management.

---

## 🧠 Technology Stack

- **Model**: VGG16 (Transfer Learning) + Custom Dense Layers
- **Interface**: Flask Web Application
- **Dataset**: Collected from [Kaggle](https://www.kaggle.com/)  
- **Accuracy**: ~91% on validation data

---

## 🧪 Key Features

- Upload an image through a browser-based form
- Predict the waste category using the trained model
- Display results instantly in the browser

---

## 🚀 How to Run Locally

### 1️⃣ Install Dependencies
```bash
pip install tensorflow flask numpy
