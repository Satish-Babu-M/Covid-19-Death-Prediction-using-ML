# Covid-19-Death-Prediction-using-ML
**High Risk of Covid - 19 Death Prediction using Machine Learning**

**Summary**
In this project, the dataset was processed to handle missing values, create a binary target variable ('DIED') based on the date of death, and address pregnancy values for males and females. Columns with the highest missing values percentage were dropped, and missing values labeled as 97, 98, or 99 were removed. Exploratory data analysis included visualizations of categorical features' distribution by death status, age distribution, and box plots showing relationships between sex, age, and death. Notable findings include an age-based analysis indicating that males and females above 55 have a higher likelihood of death.Additionally, logistic regression modeling was employed, achieving an accuracy of 94% with insightful feature importance and principal component analysis (PCA). Subsequently, random undersampling was applied to address class imbalance, resulting in a balanced dataset. Logistic regression evaluation metrics post-undersampling indicated a high accuracy (91%), precision (90%), recall (93%), and F1-score (91%). The confusion matrix emphasized the model's improved ability to correctly classify instances, underscoring the significance of addressing class imbalance in enhancing model performance for predicting the target variable 'DIED.'The project aims to contribute to building a predictive model for High Risk of Covid - 19 Death Prediction, with a focus on feature engineering and interpretation.

**#What further ana;lysis can be done?**
1. Feature Importance Refinement:
    Revisit feature importance analysis using techniques like Recursive Feature Elimination (RFE) to iteratively remove less important features and observe the impact on model performance.
2. Cross-Validation:
    Conduct cross-validation to assess the model's stability and generalizability. This involves training and evaluating the model on multiple subsets of the data to obtain a more robust estimate of its performance.
3. Different Models:
    Consider trying different classification algorithms (e.g., Decision Trees, Random Forests, Support Vector Machines) to see if a different model architecture performs better for your specific dataset.
4. Hyperparameter Tuning:
    Optimize hyperparameters for the logistic regression model using techniques like grid search or randomized search to find the parameter values that result in the best performance.
