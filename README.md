# Premier League Match Outcome Prediction

![Premier League](./eplLogo.jpeg)

This project explores whether match outcomes in the **English Premier League (EPL)** can be predicted using historical match statistics.

The project was developed as the **final project for the Introduction to Pattern Recognition course** during my **Bachelor's degree in Computer Engineering at Erciyes University**.

The objective was to apply machine learning techniques to sports analytics data and evaluate the ability of models to predict match results.

---

## Project Overview

Using historical match data from multiple Premier League seasons, the project attempts to classify match outcomes based on statistical features.

The prediction task is formulated as a **classification problem** where the model predicts match results based on historical performance indicators.

Possible outputs include:

- Home Win
- Away Win
- Draw

---

## Dataset

The dataset contains match statistics from two Premier League seasons:

- 2020-2021
- 2021-2022

Files included in the repository:

- `2020-2021.csv`
- `2021-2022.csv`

These datasets include features such as:

- Goals scored
- Shots
- Shots on target
- Possession
- Fouls
- Match statistics

The data was used to train and evaluate predictive models.

---

## Machine Learning Workflow

The following steps were applied in the project:

1. Data loading and preprocessing
2. Feature selection
3. Dataset merging across seasons
4. Model training
5. Model evaluation

The workflow is implemented in `main.ipynb`.

---

## Model Evaluation

The trained model was evaluated using common classification metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score

These metrics help determine how well the model predicts match outcomes.

---

## Project Structure

    IPR-Final-EPL
    ├── main.ipynb
    ├── 2020-2021.csv
    ├── 2021-2022.csv
    ├── IPR_final.pdf
    ├── eplLogo.jpeg
    └── README.md

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

---

## Development Context

This project was developed as the **final assignment for the Introduction to Pattern Recognition course**.

The goal was to build a machine learning pipeline using a real-world dataset and evaluate classification performance.

---

## Author

**Furkan Yilmaz**

Developed during my **Bachelor's degree in Computer Engineering at Erciyes University**.

Currently pursuing an **M.Sc. in Computer Science at HAW Kiel University of Applied Sciences (Germany)**.

