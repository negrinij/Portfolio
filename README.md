# Welcome to my GitHub Page

Here you can find some of the recent projects I have been working on. If you would like to know more about myself, please check the [About Me](https://github.com/negrinij/Main/edit/main/README.md) section.

I have also worked on Exploratory Data Analysis (EDA's) that can be found [here](https://negrinij.github.io/EDA/).

## Machine Learning Projects

### [Santander Customer Transaction Challenge](https://nbviewer.jupyter.org/github/negrinij/Santander-Transaction/blob/master/Santander-Customer-Transaction.ipynb)

- A Kaggle challenge where the goal is to predict if Santander's clients will execute a specific transaction;
- The dataset provided by the bank is anonymised, and it is a representation of real customer data;
- It is a binary classification problem, with 200 features and 200.000 samples for each the train and test sets;
- Light GBM has shown to be an interesting choice for this dataset. The final model AUC is approximately 90% for both train and test sets;
- Preliminary tests with Logistic Regression, SVM and XGBoost have not reached AUC values above 65%. As future work, an ensemble model would be an interesting approach as well as applying ANN.

![](/Images/Santander.png)

### [Stock Market Time-series Analysis](https://nbviewer.jupyter.org/github/negrinij/Stock-Analysis/blob/master/FB-Analysis.ipynb)

- This project aims to predict Facebook (FB) next day stock price direction with Machine Learning algorithms. Daily values were retrieved (volume, open, close, low and high prices) from Yahoo! Finance website. The date range is July 2012 to November 2018;
- Technical indicators and global market indexes are used, and their influence on the forecast accuracy is analysed;
- The final dataset comprises 44 features and approximately 1600 samples from daily market data;
- The results have shown that SVM outperforms logistic regression (LR), random forest (RF) and the ensemble of these algorithms for stock movement prediction. The inherent capability of SVM to avoid overfitting contributed to this conclusion;
- Essential contributions from literature allowed the construction of a model that can forecast with similar accuracies of current published papers. As it is the case for market traders, the usage of technical indicators and global indexes have shown to be a powerful strategy to support forecast decisions.

![](/Images/FB_Res.png)
