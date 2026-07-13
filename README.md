# SCT_ML_3
my 3rd internship project!!
# 🐱 Dog vs Cat Image Classification using Support Vector Machine (SVM)

## 📌 Objective

The objective of this project is to build a Support Vector Machine (SVM) model that can classify images as either **Cat** or **Dog**.

This project was completed as **Task 03** of my Machine Learning Internship at SkillCraft Technology.

---

## 📂 Dataset

**Dataset:** Dogs vs Cats Dataset

The original dataset contains images of cats and dogs.

For this project, a subset of:
- 1000 Cat Images
- 1000 Dog Images

was used to train the SVM model.

---

## 🛠️ Technologies Used

- Python
- NumPy
- OpenCV
- Matplotlib
- Scikit-Learn
- Google Colab

---

## 📖 Workflow

1. Import required libraries.
2. Load the dataset.
3. Create a subset of images.
4. Read images using OpenCV.
5. Resize every image to **64 × 64** pixels.
6. Flatten each image into a one-dimensional feature vector.
7. Create labels:
   - Cat → 0
   - Dog → 1
8. Split the dataset into training and testing sets.
9. Train the Support Vector Machine (SVM) model.
10. Predict image classes.
11. Evaluate the model using Accuracy and Classification Report.

---

## 📊 Model Performance

**Accuracy:** **64.25%**

Classification Metrics:

- Precision: 64%
- Recall: 64%
- F1-Score: 64%

---

## 📷 Sample Image

Before Color Conversion

![Sample Image](Dog_Cat_SVM_CAT_IMG_1.png.jpg)

After Converting BGR to RGB

![RGB Image](Dog_Cat_SVM_CAT_IMG_2.png.jpg)

---

## 📈 Classification Report

![Classification Report](Dog_Cat_SVM_CLASSIFICATION_REPORT.png.jpg)

---

## 📚 What I Learned

- Difference between Regression, Classification and Clustering
- Working with image datasets
- Reading images using OpenCV
- Image preprocessing
- Image resizing
- Feature extraction using flattening
- Creating labels for image classification
- Training an SVM classifier
- Evaluating a classification model

---

## ✅ Conclusion

In this project, I successfully implemented a Support Vector Machine (SVM) to classify cat and dog images.

This project helped me understand the complete image classification workflow, including image preprocessing, feature preparation, model training, prediction, and evaluation.

---

## 📁 Project Structure

```
SCT_ML_3/
│
├── Dog_Cat_SVM.ipynb
├── requirements.txt
├── README.md
└── images/
```

---

## 👨‍💻 Author

**Samyak Jain**

Machine Learning Intern at SkillCraft Technology
