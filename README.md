# Welcome to my GitHub Page

Here you can find some of the recent projects I have been working on. If you would like to know more about myself, please check the [About Me](https://github.com/negrinij/Main/edit/main/README.md) section.

I have also worked on Exploratory Data Analysis (EDA's) that can be found [here](https://negrinij.github.io/EDA/).

## Machine Learning Projects

### [HAM10000: Skin Lesion Classification](https://nbviewer.jupyter.org/github/negrinij/HAM10000-SkinCancer/blob/master/ham10000-analysis-and-model-comparison.ipynb)

- The HAM10000 dataset is composed of 10.015 dermatoscopic images of pigmented skin lesions. The dataset present seven classes of skin lesions, including Melanoma, a malignant type of cancer;
- Melanocytic nevi is the dominant class in the dataset (67%). 
- Melanoma, seems to be more common in the ages of 45 to 70. Males represent 62% of the incidence of this type of lesionIt could result in a bias towards this type of os skin lesion;
- From the three different architectures shown in this study, XCeption achieved better accuracy in the test set (~80%);
- The dataset is unbalanced, for such cases the accuracy metric can give us a false perception of the model reliability. An analysis using F1-score and possible improvements are suggested

![](/Images/HAM10000.png)

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

### [UCI Heart Attack Dataset](https://nbviewer.jupyter.org/github/negrinij/UCIHeartAttack/blob/main/heart-attack-uci-dataset-89-acc-test-set.ipynb)

- Binary Classification problem using a amall dataset with approximately three hundred samples and fourteen features
- Overall, the dataset is balanced between both classes of the Target feature. However, there is an expressive unbalance regarding gender, where Males compose ~70% of the data
- A higher concentration of positive Heart Attack samples appears in the region where lower values for Age and Cholesterol and higher values of Heart rate meet
- Data Scaling, OneHotEncoding and the use of KMean for the creation of new features did not improve model generalisation
- In the training set results, the model shows a tendency for False Positives
- Optuna Optimisation library is used to choose the best model between: Random Forest and Logistic Regression. Preliminary tests excluded SVM and KNN as options
- Best Model is Logistic Regression with 89,7% Accuracy. The models were finely tuned with Optuna Library
![](/Images/UCI.png)

