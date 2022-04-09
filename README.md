# Detecting Fake News Using Machine Learning

Kaggle link: https://www.kaggle.com/code/johnmatzakos/detectfakenewsml/notebook

Programming language: Python

Packages used:
- Pandas
- NLTK
- Scikit Learn
- Matplotlib
- and more

Results:

| Classifier                   | 	Class | Precision | Recall | F1-Score | Accuracy | AUC Score |
|-------------------------------------|----------------|--------------------|-----------------|-------------------|-------------------|--------------------|
| Naive Bayes                | 0              | 83\%               | 81\%            | 82\%              | 82.49\%           | 89.48\%            |
|                                     | 1              | 82\%               | 84\%            | 83\%              |                   |                    |
| Support Vector Machines    | 0              | 85\%               | 86\%            | 85\%              | 85.70\%           | 85.71\%            |
|                                     | 1              | 87\%               | 85\%            | 86\%              |                   |                    |
| Binomial Linear Regression | 0              | 85\%               | 85\%            | 85\%              | 92.71\%           | 85.59\%            |
|                                     | 1              | 86\%               | 86\%            | 86\%              |                   |                    |
| CART Decision Tree        | 0              | 86\%               | 82\%            | 84\%              | 84.79\%           | 84.67\%            |
|                                     | 1              | 84\%               | 88\%            | 86\%              |                   |                    |
| k Nearest Neighbor         | 0              | 89\%               | 86\%            | 87\%              | 88.15\%           | 88.06\%            |
|                                     | 1              | 87\%               | 90\%            | 89\%              |                   |                    |
| Passive Aggressive         | 0              | 82\%               | 85\%            | 83\%              | 83.77\%           | 83.82\%            |
|                                     | 1              | 86\%               | 82\%            | 84\%              |                   |                    |
| Ada Boost                  | 0              | 87\%               | 88\%            | 87\%              | 87.76\%           | 87.75\%            |
|                                     | 1              | 88\%               | 88\%            | 88\%              |                   |                    |
| Random Forest              | 0              | 93\%               | 90\%            | 92\%              | 92.13\%           | 97.59\%            |
|                                     | 1              | 91\%               | 94\%            | 93\%              |                   |                    |

