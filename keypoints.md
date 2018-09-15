#1. Data Acquisition
Read your data, in the right format.  
- If working in a team: set up a conducive environment  
(Git, Version Control)  
- Be **very** familiar with your workspace, your tools, your IDE  
- Outline your plan  

# 2. Structure your project
* Documents
  * Finhacks
    * project.ipynb
    * project.rmd
    * project.R
    * assets
      * glossary.txt
      * description.txt
    * data_input
    * styles
      * styles.css
    * .gitignore
* Lay out the document structure
  * Chap.1 Background
  * Chap.2 Data Transformation..
* Do work that you can be proud of  


# 3.Writing Code
Importance of [Style Guide](https://google.github.io/styleguide/Rguide.xml)
Use comments a lot!

# 4.Final Output
Look at the requirements and pay attention to details
- PDF, Word Doc
- Use tools like RStudio's Knitr and Jupyter (Notebook and Lab) to help you make your end product more polished
- Use pagination
- Use formatting (markdown)
  - h1,h2,h3,ul,img,links
- Use breaks
- Include images

# 5.Machine Learning Models  
How to build a great machine learning model

Your work is done when you can prove to yourself in some ways that your model cannot be further improved upon.

## 5.1 Develop your first model
- Focus on speed and execution  
- Don't worry about whether it's the best one yet

## 5.2 Get your cross-validation accuracy
- How your model perform on unseen data  
- Look at your errors
  - Residual plots
  - Heteroskedasticity
  - Misclassification error
  - ACF / PACF
- What you did poorly is more informative than what you did well in the first place  

## 5.3 Bias-Variance Tradeoff
- If you're not happy with your model, most likely you're overfitting / underfitting
- If model obtains very high accuracy on train data, but no accuracy on test data: overfitting  
- Linear Regression: increasing polynomial terms adds variance
- Nearest Neighbors: change your k

##5.4 Focus on Iterating
- Feature Selection  
- Feature Engineering  
- Dimensionality  
- Parameterization

## 5.5 Focus on your train, test, cross-validation
- Your test data can only be used once
- Test data is used only as an unbiased estimate of your model's performance  
- You do not want to mistakenly confuse your "test data" as part of your training. Your test data should never be used at all - used only once at the very end to obtain an unbiased estimate of its performance

## 5.6 Look at your performance indicators
- Accuracy is rarely useful in real life
- Precision vs Recall  
- ROC Curve  

## 5.7 Speed consideration
- Training Speed
  - Neural Network, RF.. are notoriously slow at training
- Prediction Speed
  - kNN are slow at prediction when used on data with large dimensions  


