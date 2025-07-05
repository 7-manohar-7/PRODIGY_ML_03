# 🐱🐶 PRODIGY_ML_03 – Cat vs Dog Image Classification using SVM

This project classifies images as either a cat or a dog using a Support Vector Machine (SVM) classifier trained on the Kaggle Dogs vs. Cats dataset.

---

## 📌 Project Description

Image classification is a key task in computer vision. This project demonstrates how traditional machine learning models like SVM can be used to classify pet images effectively.

---

## 🛠 Tech Stack / Tools Used

- **Language**: Python
- **IDE**: Jupyter Notebook
- **Libraries**:
  - NumPy
  - Pandas
  - OpenCV
  - Matplotlib
  - Scikit-learn
- **Dataset**: Dogs vs. Cats Dataset (Kaggle)

---

## 🧠 Problem Statement

Given a labeled image dataset of cats and dogs, can we build a classifier that accurately identifies whether an input image contains a cat or a dog?

---

## 🧪 Solution Approach

1. **Data Collection**:
   - Used a subset of the Kaggle Dogs vs. Cats dataset for training.
2. **Preprocessing**:
   - Resized images to 64x64
   - Converted to grayscale
   - Flattened image arrays for SVM input
3. **Model Building**:
   - Trained an SVM classifier using `scikit-learn`
   - Split data into training and testing sets
4. **Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - Sample image predictions

---

## 💻 Installation & Setup

```bash
git clone https://github.com/yourusername/cat-dog-svm.git
cd cat-dog-svm
pip install -r requirements.txt
jupyter notebook
