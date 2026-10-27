# Adult_income_fairness_analysis
Evaluating algorithmic fairness in Adult Census Income prediction using Logistic Regression and Fairlearn. This project explores demographic disparities across sex and race, applies fairness mitigation techniques, and analyses the trade-offs between predictive performance, fairness metrics, and model errors.
# Fairness in Machine Learning: Adult Census Income Prediction

## Project Overview

This project evaluates algorithmic fairness in a Logistic Regression model using the Adult Census Income dataset. It examines predictive performance and demographic disparities across sex and race groups, then evaluates fairness mitigation using Fairlearn.

## Objectives

- Explore and prepare the Adult Census Income dataset.
- Train and evaluate a baseline Logistic Regression classifier.
- Measure group-level fairness using metrics such as True Positive Rate, False Positive Rate, Equalized Odds Difference, and Disparate Impact Ratio.
- Apply fairness mitigation separately for sex and race.
- Compare predictive performance, fairness metrics, and changes in model predictions.
- Discuss the limitations and ethical implications of algorithmic fairness.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Fairlearn
- Jupyter Notebook / Google Colab

## Key Findings

The baseline model achieved approximately 85% accuracy and a ROC-AUC of 0.898. The fairness mitigation experiments demonstrated that improving some fairness measures can affect predictive performance and other group-level outcomes.

Sex-based and race-based mitigation produced different trade-offs, illustrating why fairness should be evaluated across multiple measures rather than through a single score.

## Dataset

The project uses the Adult Census Income dataset, available through the [UCI Machine Learning Repository](https://doi.org/10.24432/C5XW20) and [Kaggle](https://www.kaggle.com/datasets/uciml/adult-census-income).

## Limitations

The dataset reflects historical socioeconomic patterns. The results depend on the selected data, preprocessing, model, decision threshold, and evaluation split. Small demographic subgroups require particular caution. This educational analysis does not establish causation or prove that a model is suitable for real-world consequential decisions.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Obtain the dataset from the source linked above.
3. Follow the notebook's data-loading instructions.
4. Install any required dependencies if they are not already available.
5. Run the cells from top to bottom.

## Project Purpose

This project demonstrates practical skills in machine learning, model evaluation, responsible AI, and fairness analysis.
