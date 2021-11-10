## Project 1: Prediction of Customer Churn in Telecom Industry

### Project Overview
- In the Indian Telecom Industry, approximately 80% of revenue comes from the top 20% customers who can be termed as high-value customers. Since the Telecom industry faces  an average of 15-25% annual churn rate, this project was built to help predict the customers who are at high risk of Churn, such that the Company can look into the requirements of the Customer earlier and provide them with offers and benefits in order to retain them.
- Since Prepaid Model is most commonly used in India, Customer churn was predicted based on their usage of Service. The Customer Activity for a span of 3 months was observed and analysed to find Patterns and was used to Predict if the Customer was going to churn or not.
- As the dataset contained a large number of features to predict from, the feature size was reduced using dimensionality reduction technique - **PCA**.
- The dataset was highly imbalanced, as the number of customers churning contributed to only 9% of the entire dataset. This was handled using **SMOTE** techniques.
- The final model was able to predict **84%** of the customers who intended on churning.
- A model for identifying the top features that led to customers churning was also built.

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
