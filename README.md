# Landcover_Classification_project

# 🌱 Land Cover Classification using NDVI and Logistic Regression

This project aims to classify land cover types such as **water**, **forest**, **grass**, etc., based on NDVI (Normalized Difference Vegetation Index) time-series data from satellite imagery.  
The entire pipeline includes **data cleaning**, **preprocessing**, and training a **multinomial logistic regression** model using `scikit-learn`.

---

## 📌 Problem Statement

Use NDVI values collected over 27 time-stamped features to predict the type of land cover. The classification includes:
- Forest
- Farm
- Water
- Grass
- Orchard
- Impervious surfaces

---

## 🧠 Techniques Used

- Data cleaning and imputation (handling missing NDVI values)
- Label encoding for categorical class labels
- Model training using Logistic Regression
- Evaluation via classification report and confusion matrix
- Final test predictions and CSV submission

---

## 📊 Results

- **Validation Accuracy**: 95.3%
- **F1-Scores**:
  - Forest: 0.99
  - Farm: 0.85
  - Impervious: 0.85
  - Grass: 0.77
  - Water: 0.74
  - Orchard: 0.17

---

## 📁 Files Included

- `notebook.ipynb`: Full Jupyter/Colab code
- `submission.csv`: Final predicted output format
- `project_explanation.pdf`: High-level write-up
- `conf_matrix.png`: Confusion matrix of validation
- `class_dist.png`: Class distribution in training set

---

## 🚀 How to Run

1. Clone the repo
2. Upload your own NDVI dataset if different
3. Run the notebook (recommended in Google Colab)
4. Generate predictions and export the `submission.csv`

---

## 📚 Skills & Tools

`Python` · `scikit-learn` · `Pandas` · `Logistic Regression` · `Geospatial ML` · `NDVI Analysis` · `Multiclass Classification`

---

## 👤 Author

**Jatin Bhardwaj**  
Connect on [LinkedIn](https://www.linkedin.com/in/jatin-bhardwaj2004) · Drop a ⭐ if you found this helpful!
