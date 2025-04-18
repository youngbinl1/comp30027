# Music Genre Classification using the GTZAN Dataset  
*COMP30027 Machine Learning – Semester 1, 2023*  
*The University of Melbourne*

---

## 🎵 Overview

This project focuses on **music genre classification** using the well-known **GTZAN Dataset**. It involves extracting and analyzing audio features from music clips and applying machine learning models to classify them into genres.

---

## 📁 Dataset Source

> Andrada Olteanu, James Wiltshire, Lauren O’Hare and Minyu Lei.  
> **GTZAN Dataset – Music Genre Classification**  
> [Kaggle Link](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

This dataset was edited specifically for the COMP30027 Machine Learning course.

- **Column 1**: Filename of the audio clip  
- **Columns 2–57**: Extracted audio features  
- **Column 58**: Genre class label

---

## 👥 Authors

- **Sakshi Godbole**  
- **Youngbin Lee**

---

## 🧠 How to Use

1. Clone or download this repository to your local machine.
2. Ensure the dataset CSV file is available locally.
3. Open the code notebook or script.
4. **Below the `preprocess()` function**, locate the `# Load datasets` comment.
5. Replace the dataset path(s) with the correct path on your local machine.

```python
# Example:
data = pd.read_csv("your/local/path/to/dataset.csv")
```

6. Run each block of code **sequentially** for correct execution.

---

## 🛠️ Features

- Data preprocessing with scaling and cleaning
- Feature analysis and visualization
- Machine learning models for genre classification
- Evaluation of model performance (accuracy, confusion matrix, etc.)

---

## 📊 Results

The classification results, evaluation metrics, and plots will be generated automatically when the notebook/script is run.
