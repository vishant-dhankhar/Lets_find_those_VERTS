# 🔍 Let's Find Those VERTS

This project predicts whether a person is an **Introvert** or **Extrovert** based on behavioral and social traits, using machine learning. The project was submitted to a Kaggle competition and achieved a strong score on the public leaderboard.

---

## 🧠 Project Highlights

- ✅ Built using Python, pandas, and Scikit-learn
- ✅ Trained a logistic regression model for classification
- ✅ Applied data imputation, label encoding, and standard scaling
- ✅ Achieved **Kaggle public leaderboard score: 0.902024**
- ✅ Clean, readable, and reproducible notebook

---

## 📊 Features Used for Prediction

The model was trained using the following input features:

- `Time_spent_Alone`
- `Stage_fear`
- `Social_event_attendance`
- `Going_outside`
- `Drained_after_socializing`
- `Friends_circle_size`
- `Post_frequency`

Each feature represents a behavioral trait derived from a questionnaire or observation.

---

## 📁 Files in This Repository

| File/Folder                  | Description                                        |
|-----------------------------|----------------------------------------------------|
| `lets-find-those-verts.ipynb` | Main notebook with all code                      |
| `submission/submission.csv` | Final Kaggle-formatted predictions                |
| `requirements.txt`          | Python libraries used                             |
| `data/`                     | Contains `train.csv`, `test.csv`, etc.            |

---

## 📦 Dataset

The dataset used in this project was sourced from the Kaggle competition:  
[🔗 Playground Series - Season 5, Episode 7](https://www.kaggle.com/competitions/playground-series-s5e7)

   - `train.csv`
   - `test.csv`
   - `sample_submission.csv`


---

## 🛠️ Workflow Overview

1. **Data Preprocessing**
   - Replacing missing values using mean (for numeric) and mode (for categorical)
   - Mapping categorical labels to numerical format
   - Feature scaling using StandardScaler

2. **Model Building**
   - Trained Logistic Regression using Scikit-learn

3. **Submission**
   - Converted numeric predictions to labeled format (`Introvert` / `Extrovert`)
   - Created `submission.csv` file for Kaggle

---

## 🏁 Kaggle Results

| Metric         | Score     |
|----------------|-----------|
| Public LB Score| **0.902024** |

---

## 🙋‍♂️ Author

**Vishant Dhankhar**  
Passionate about building ML models that work in the real world.

---

