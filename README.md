My First Kaggle Competition

URL: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

Author: Jack Driscoll
Date: July 2, 2021

Submitted as of July 3, 2021

Ranking: 10856 / 13559 (not bad eh?)
Root mean squared error on test set: 0.18887
Model saved to 'model.joblib'


I wanted to use this getting started competition to review Chapter 2 in the Hands on Machline learing book I'm reading. It covered an example of housing data so this one seemed perfect. I learned a lot from my breif time on this competition and I strengthed many of the topics I learned in the book. 

Some things I could have done more if I wanted to spend more time on this problem would be to utilize more features or different combinations of features. I didn't want to have to mess with data cleaning too much at the moment so I chose the top features that had all rows filled and a numerical data type. These features ended up being the top 5 most correlated features according to the corr matrix anyway. I could have also added a step to the transformer that only chose the top 5 features but I didn't and manually did that for both the train and test set. 

Looking forward to more!


