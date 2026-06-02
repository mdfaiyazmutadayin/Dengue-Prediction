# Dengue-Prediction
## Project Overview

Dengue is a mosquito-borne viral disease that can range from mild fever to severe, life‑threatening complications. Early identification of patients at higher risk can support faster clinical decision-making and better allocation of healthcare resources. This repository contains my **Machine Learning course project** focused on predicting **dengue outcomes** from structured patient information and laboratory indicators. The work is organized as a single, reproducible **Jupyter Notebook** that demonstrates the typical end-to-end workflow used in applied machine learning.

## What this project does

In this project, I use patient **demographic features** (such as age and gender), **test results** (e.g., NS1 and IgM/IgG indicators), and selected contextual attributes (such as area type and house type) to explore patterns in the data and build a predictive model for the target outcome. The notebook includes **data loading**, **data cleaning**, **exploratory data analysis (EDA)**, and multiple **visualizations** to understand feature distributions and relationships with the outcome. I also create derived features (for example, age group bins) to make trends easier to interpret and to support model performance.

## Machine Learning workflow

The notebook follows a standard ML pipeline:
- Preparing the dataset (handling missing values, selecting relevant columns, and encoding categorical variables where required)
- Splitting data for training and evaluation
- Training classification model(s) to predict the dengue outcome
- Evaluating results with suitable metrics and interpreting what the model learns

Along the way, charts and summary tables are used to communicate insights clearly. The focus is not only on building a model, but also on understanding the data and documenting each step so the workflow is easy to follow and repeat.

## Repository contents

- `Dengue_Prediction.ipynb`: Main notebook containing the full analysis, visualizations, and modeling steps.
- `README.md`: Project summary and usage notes.

## Notes

This project was created as part of a **machine learning course** for learning and practice. The dataset and results are intended for educational purposes and should not be treated as medical advice or a clinical diagnostic tool.
