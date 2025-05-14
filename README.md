# Mushroom Edibility Classification Using Machine Learning

This repository contains a cleaned version of the Mushroom Dataset for binary classification tasks. The original dataset is sourced from the UCI Machine Learning Repository, and this version has been preprocessed for improved usability and performance in machine learning models.

## 📊 About the Dataset

The dataset includes various features related to mushroom characteristics and is intended to predict whether a mushroom is **edible** or **poisonous**.

### 🔧 Cleaning & Preprocessing Techniques Applied:
- **Modal Imputation** for handling missing values
- **One-Hot Encoding** for categorical variables
- **Z-Score Normalization** for numerical features
- **Feature Selection** to retain the most relevant features

### 🧠 Features (9 Columns Total):

| Feature         | Description                  |
|----------------|------------------------------|
| Cap Diameter    | Diameter of the mushroom cap |
| Cap Shape       | Shape of the mushroom cap    |
| Gill Attachment | How the gills are attached   |
| Gill Color      | Color of the gills           |
| Stem Height     | Height of the stem           |
| Stem Width      | Width of the stem            |
| Stem Color      | Color of the stem            |
| Season          | Season of mushroom growth    |
| Target Class    | 0 = Edible, 1 = Poisonous    |

### 🎯 Target Variable
- **0** = Edible  
- **1** = Poisonous

## 📎 Dataset Source

You can access the dataset here:  
[🔗 Mushroom Dataset on Kaggle](https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset)

## 💡 Usage

This dataset is ideal for binary classification models and can be used to practice data preprocessing, model training, and evaluation tasks in machine learning workflows.

---

Feel free to fork the repo, run your experiments, and contribute!
