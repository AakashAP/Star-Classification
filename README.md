# STAR CLASSIFICATION

This Project aims to Develop a Deep Learning Model with Tensorflow to Classify Celestial Radiation as originating from a Galaxy, Star or Quasar.

This Work was Undertaken as Part of a Machine Learning Projects for a College Course

The Repository includes a Jupyter Notebook that Implements Advanced Data Preprocessing, Exploratory Data Analysis (EDA), Mdoel Training and Evaluation


## DATASET

A Publicly Available Dataset was used for Training and Testing. The Dataset comprises multiple Columns representing Different Aspects of Rediation Characteristics, Providing a Rich Feature Set for Model Training and Evaluation

### DIRECTORY STRUCTURE

**Dataset/Dataset.csv** - The Dataset leveraged for Empirical Assessment
**Notebook.ipynb** - The Primary Notebook containing the Actual Code

### DEPENDENCIES

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

---

## MODEL DETAILS

**Model Training & Evaluation**
  There are Total of 3 Machine Learning Models
  - Support Vector Machine (SVM)
  - KNeighbor Classifier (KNN)
  - Random Forest Classifier

  I Have Used **Accuracy**, **Precision**, **Recall**, **Confusion Matrix** and **Classification Report** to Evaluate our Model

**Results**
  The Resulted Accuracy obtained with Different Models
  - Support Vector Machine (SVM) -> 96.2%
  - KNeighbor Classifier (KNN) -> 93.5%
  - Random Forest Classifier -> 97.7%

The **Random Forest Classifier** Stands Out by Outperforming Other Models with 97.7% of Accuracy

---

## GETTING STARTED

**Clone the Repository**
  Clone the Repository to your Local Machine
  ```bash
  git clone https://github.com/AakashAP/Star-Classification.git
  ```

**Open in Code Editor**
  Navigate to the Project Folder and Open it in Jupyter Notebook and Execute in Sequential Order