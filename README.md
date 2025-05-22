
# ML Assignment – Math Question Classification

This project presents a machine learning pipeline for classifying 10,189 mathematical questions into 8 topical categories using text-based and domain-informed features. It explores classical ML models (Logistic Regression, Linear SVM, Random Forest) and a hard voting ensemble. The dataset is sourced from [Kaggle](https://www.kaggle.com/competitions/classification-of-math-problems-by-kasut-academy).

---

## Instructions to Run the Code

### Requirements
- Python 3.8 or higher
- Jupyter Notebook (Anaconda, VSCode, or standalone)
- Required packages:
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - wordcloud
  - numpy

Install dependencies:
```bash
pip install -r requirements.txt
```

---

### Folder Structure

Make sure your project directory is organized like this:

```
ML_assignment/
├── ML_assignment.ipynb       # Main notebook
├── README.md                 # Project overview and instructions
├── requirements.txt          # Python dependencies
├── data/
│   └── train.csv             # Dataset file
```

---

### How to Run

1. Clone or download the repository.
2. Ensure the dataset is located at `data/train.csv`.
3. Open `ML_assignment.ipynb` using Jupyter Notebook.
4. Run all cells from top to bottom.

The notebook performs:
- Data loading and exploration
- Text preprocessing and feature extraction (TF-IDF + handcrafted features)
- Model training: Logistic Regression, Linear SVM, Random Forest
- Evaluation using macro F1, micro F1, accuracy
- Ensemble voting
- Interpretability analysis (feature importance plots)

---

### Author

Naif Alawad  
Module: UFCFMJ-15-M (Machine Learning and Predictive Analytics)  
University of the West of England – MSc Data Science
