# Bank Term Deposit Subscription Classification

This repository contains two notebooks showcasing the classification of a dataset related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (`variable y`).

## Notebooks

1. **classification_during_interview.ipynb**
   - This notebook was created during a technical interview, with a limited timeframe. It demonstrates the initial steps and insights I gathered within the interview duration.

2. **post_interview_classification.ipynb**
   - This notebook was revisited after the interview without time constraints. It provides a more thorough exploration of the dataset with a clear focus on improving the initial approach.

## Dataset

The data used is from a direct marketing campaign dataset for a Portuguese banking institution. The objective is to classify whether a client will subscribe to a term deposit based on several features collected from phone calls.

### Dataset Features

- **Age**: Client’s age.
- **Job**: Job type of the client.
- **Marital**: Marital status.
- **Education**: Level of education.
- **Default**: Credit default indicator.
- **Balance**: Account balance.
- **Housing**: Housing loan status.
- **Loan**: Personal loan status.
- **Contact**: Communication type.
- **Day**: Last contact day of the month.
- **Month**: Last contact month of the year.
- **Duration**: Last contact duration, in seconds.
- **Campaign**: Number of contacts performed during this campaign.
- **Pdays**: Number of days since the client was last contacted.
- **Previous**: Number of contacts performed before this campaign.
- **Poutcome**: Outcome of the previous marketing campaign.
- **Target (y)**: Whether the client subscribed to a term deposit.

## Models

The following machine learning algorithms were applied:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Naive Bayes

## Results

Performance metrics such as accuracy, precision, recall, and F1-score were used to evaluate the models.

