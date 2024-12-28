# Data-Visualization-Final-Project

## Project Description

This project performs a Principal Component Analysis (PCA) on the Iris dataset to reduce the number of numeric variables and address multicollinearity. PCA helps in producing a few features that explain most of the variability in the dataset.

### Problem Statement

When faced with a dataset with many numeric variables that may be highly correlated, it's beneficial to reduce the number of variables. PCA helps achieve this by creating new features that capture the majority of the data's variability.

### Structure

1. **Introduction**: Brief introduction to the project and its objectives.
2. **Description and Summary of the Dataset**: Detailed description of the Iris dataset.
3. **Data Exploratory Analysis**: 
   - Six comparisons for the four quantitative variables.
   - Scatterplot and correlations between all quantitative variables using `pairs.panels` in R.
4. **Principal Component Analysis**:
   - Performing PCA using the `prcomp()` function.
   - Interpretation of the values and parameters obtained from the `prcomp` object.
5. **Orthogonality Checking**: Checking the orthogonality of principal components.
6. **Plotting PCA**:
   - Creating biplots to visualize PCA results.
   - Interpretation of biplots.
7. **Multinomial Logistic Regression and Confusion Matrix**:
   - Using PC1 and PC2 for multinomial logistic regression.
   - Calculating accuracy and misclassification errors (sensitivity and specificity for each species).
8. **Conclusion**: Discussing the advantages, disadvantages, and applications of PCA.
9. **Summary**: Summarizing the entire report.

### R Functions Used

- `prcomp()`
- `pairs.panels()`
- `biplot()`
- `predict()`
- `multinom()`

## Conclusion

The project demonstrates the effectiveness of PCA in reducing dimensionality and addressing multicollinearity in the Iris dataset. The analysis includes detailed interpretations of PCA results, orthogonality checks, and accuracy assessments using multinomial logistic regression.
