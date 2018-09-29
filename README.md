# Titanic: Machine Learning from Disaster

My submission to the "Titanic: Machine Learning from Disaster" Kaggle competition. Two solutions in the form of Jupyter Notebooks can be found in this repository; one focuses on the more traditional machine learning algorithms (decision tree, forest, logistic regression, and so on) while the other focuses on using neural networks with PyTorch.

As this is my first submission to Kaggle, the main goals are to learn more about data analysis and machine learning algorithms, as well as, get some practice with the most relevant Python libraries related to datascience.

## Competition Description

> The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.
>
> One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
>
> In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

Source: <https://www.kaggle.com/c/titanic>

## Installation

1. Python 3 and pip.
2. Set up a virtual environment (optional, but recommended).
3. Install dependencies using pip: ``pip install -r requirements.txt``.

## Submissions

### Machine learning algorithms

Kernel@GitHub: [ml/surviving-the-titanic.ipynb](https://github.com/davidtvs/kaggle-titanic/blob/master/ml/surviving-the-titanic.ipynb)  
Kernel@Kaggle: [Surviving the Titanic step-by-step with groups](https://www.kaggle.com/dr1t10/surviving-the-titanic-step-by-step-with-groups?scriptVersionId=5237095)

Step-by-step solution focusing on traditional machine learning algorithms and handling, analysing and visualizing data. Core libraries:
- [pandas](https://pandas.pydata.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

Achieves a public test set score of 80.861% (top 8%).

### Neural network with PyTorch

Kernel@GitHub: [pytorch/surviving-the-titanic.ipynb](https://github.com/davidtvs/kaggle-titanic/blob/master/pytorch/surviving-the-titanic.ipynb)  
Kernel@GitHub: [TitanicNet with PyTorch](https://www.kaggle.com/dr1t10/titanicnet-with-pytorch?scriptVersionId=5419927)

Focuses on implementing functionalities similar to scikit-learn to facilitate model building, training, cross-validation, and grid search.

Achieves a public test set score of 80.861% (top 8%).
