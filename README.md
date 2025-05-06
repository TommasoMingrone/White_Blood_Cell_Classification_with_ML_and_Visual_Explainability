# White Blood Cell Classification with ML and Visual Explainability 🧬🔬

This project focuses on the classification of white blood cell (WBC) types using machine learning techniques, combining standard supervised learning with visual explainability tools such as attention maps. The aim is to build an interpretable model that supports hematological image analysis while promoting transparency — a crucial aspect in medical AI applications.

> The entire project was developed independently and autonomously, including data selection, preprocessing, model development, and visualization.

---

## 🧾 Project Overview

This repository contains:
- 🧠 A **Jupyter Notebook** that walks through the entire pipeline: data loading, preprocessing, CNN model training, and visual explanation generation (e.g., Grad-CAM).
- 📄 A **PDF presentation** summarizing the methodology, results, and conclusions.

Non-relevant cell types such as **erythroblasts** and **platelets** were excluded, focusing solely on the classification of **white blood cells (leukocytes)**.

---

## 📊 Dataset: Blood Cells Image Dataset

📎 **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/unclesamulus/blood-cells-image-dataset)

The dataset includes **17,092 annotated images** of normal peripheral blood cells captured at the Hospital Clinic of Barcelona using the CellaVision DM96 analyzer. Each image is 360 x 363 pixels in JPG format and manually labeled by expert pathologists.

Cell categories:
- Neutrophils
- Eosinophils
- Basophils
- Lymphocytes
- Monocytes
- Immature granulocytes (promyelocytes, myelocytes, metamyelocytes)
- **[Excluded]** Erythroblasts
- **[Excluded]** Platelets (thrombocytes)

![DatasetImagePresentation](https://storage.googleapis.com/kaggle-datasets-images/2277635/3865189/405d3eefedd5bbc96b9a918d7295f749/dataset-cover.jpg?t=2022-06-27-06-23-38)

---

## 🛠️ Technologies Used

- Python 3.10
- Jupyter Notebook
- TensorFlow / Keras
- OpenCV, NumPy, Pandas
- Grad-CAM for model interpretability

---

## 📁 Files in This Repository

```plaintext
├── TommasoMingrone_ML_Classification_Project.ipynb   # Main Jupyter notebook
├── TommasoMingrone_ML_Presentation.pdf               # Summary presentation (slides)
└── README.md                                         # Project documentation
