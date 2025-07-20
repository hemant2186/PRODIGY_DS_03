<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

# Prodigy InfoTech Data Science Internship Task 3

<br>
<img src="image.jpg">
Welcome to my submission for **Task 3** of the Data Science Internship at *Prodigy InfoTech*. In this task, I have built a decision tree classifier to predict whether a customer will purchase a product or service, based on their demographic and behavioral data.

## Task Overview

Build a decision tree classifier to determine if a customer is likely to purchase a product or service. The implementation uses the **Bank Marketing dataset** from the UCI Machine Learning Repository, which contains a range of customer demographic and behavioral features.

## Dataset

For this analysis, I used the [Bank Marketing dataset from the UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). This dataset contains information collected from a Portuguese banking institution's marketing campaigns. Features include:

- Age
- Job
- Marital status
- Education
- Default status
- Balance
- Housing loan
- Personal loan
- Contact communication type
- Duration of last contact
- Campaign features (number of contacts, previous outcomes)
- Target variable: *y* (has the client subscribed to a term deposit?)


## Tools and Libraries Used

- Jupyter Notebook
- Pandas \& NumPy for data processing
- Scikit-learn for decision tree modeling
- Matplotlib \& Seaborn for visualization


## Workflow

1. **Data Preparation**
    - Loaded the dataset and performed initial inspection.
    - Handled missing values and encoded categorical variables using one-hot encoding.
    - Split the data into training and test sets for evaluation.
2. **Model Building**
    - Imported the `DecisionTreeClassifier` from Scikit-learn.
    - Trained the model on the training subset.
    - Pruned the tree by tuning hyperparameters (max_depth, min_samples_split) to prevent overfitting.
3. **Model Evaluation**
    - Predicted outcomes on the test data.
    - Assessed model performance using accuracy, precision, recall, and F1-score.
    - Visualized the decision tree structure for interpretability.

## Key Findings

- **Feature Importance:** Variables such as *duration of last contact*, *previous outcome*, and *number of contacts in current campaign* showed the strongest influence on predicting customer purchases.
- **Model Performance:** The decision tree classifier provided decent accuracy and was easy to interpret. Pruning improved generalizability and reduced overfitting.
- **Marketing Insight:** Customers with more recent and longer phone contacts were more likely to purchase products, aligning with campaign goals.


## Conclusion

A decision tree classifier is an effective and interpretable model for predicting customer purchases based on demographic and behavioral data, as demonstrated using the Bank Marketing dataset. The insights derived can help marketing teams better target their campaigns.

Thank you for reviewing my submission!

## 📬 Contact

For any inquiries or feedback regarding this project, please contact:

- [Hemant Kumar (LinkedIn)](https://www.linkedin.com/in/hemant-kumar-171472210?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
- Email: hemantkumar90089h@gmail.com

<div style="text-align: center">⁂</div>

[^1]: image.jpg

[^2]: README-1.md

[^3]: https://www.linkedin.com/in/hemant-kumar-171472210

