# Welcome to my GitHub Page

Here you can find some of the recent projects I have been working on. If you would like to know more about myself, please check the [About Me](https://github.com/negrinij/Main/edit/main/README.md) section.

## Projects

### [Santander Customer Transaction Challenge](https://github.com/negrinij/Santander-Transaction/blob/master/Santander-Customer-Transaction.ipynb)

![](https://github.com/negrinij/Main/blob/main/Images/FB.png)

- Part of a Kaggle challenge, the goal is to predict if Santander's clients will execute a specific transaction;
- The dataset provided by the bank is anonymised, and it is a representation of real customer data;
- It is a binary classification problem, with 200 features and 200.000 samples for each the train and test sets;
- Light GBM has shown to be an interesting choice for this dataset. The final model AUC is approximately 90% for both train and test sets;
- Preliminary tests with Logistic Regression, SVM and XGBoost have not reached AUC values above 65%. As future work, an ensemble model would be an interesting approach as well as applying ANN.

### [Stock Market Time-series Analysis](https://github.com/negrinij/Stock-Analysis/blob/master/FB-Analysis.ipynb)

![](https://github.com/negrinij/Main/blob/main/Images/FB.png)

- This project aims to predict Facebook (FB) next day stock price direction with Machine Learning algorithms. Daily values were retrieved (volume, open, close, low and high prices) from Yahoo! Finance website. The date range is July 2012 to November 2018;
- Technical indicators and global market indexes are used, and their influence on the forecast accuracy is analysed;
- The final dataset comprises 44 features and approximately 1600 samples from daily market data;
- The results have shown that SVM outperforms logistic regression, random forest and the ensemble of these algorithms for stock movement prediction. The inherent capability of SVM to avoid overfitting contributed to this conclusion;
- Essential contributions from literature allowed the construction of a model that can forecast with similar accuracies of current published papers. As it is the case for market traders, the usage of technical indicators and global indexes have shown to be a powerful strategy to support forecast decisions.




You can use the [editor on GitHub](https://github.com/negrinij/Main/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/negrinij/Main/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
