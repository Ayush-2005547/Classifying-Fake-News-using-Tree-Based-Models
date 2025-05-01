# Fake News Detection with Decision Trees & Random Forests

## Overview
This project demonstrates the application of **Decision Trees** and **Random Forests** for detecting fake news articles. Using a collection of textual data, we build models that classify news articles as either real or fake based on their content. The dataset is processed using **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert text into numerical features.

## Project Goals:
- Train and evaluate a **Decision Tree Classifier** and a **Random Forest Classifier**.
- Visualize the decision tree to interpret how the model splits the data.
- Compare the performance of both models using **cross-validation**.
- Examine the **feature importance** to see which words are the most influential in the decision-making process.

## Steps Taken:
1. **Data Preprocessing**:
   - Textual data converted to **TF-IDF** features for use in the machine learning models.
   
2. **Model Training**:
   - A **Decision Tree Classifier** is trained to predict fake or real news.
   - A **Random Forest Classifier** (ensemble of decision trees) is trained for comparison.

3. **Visualization**:
   - Visualized the decision tree to see the decision-making process of the model.
   
4. **Model Evaluation**:
   - Cross-validation was used to evaluate the models' accuracy, providing a more reliable estimate of their generalization performance.
   
5. **Feature Importance**:
   - Random Forest model is used to analyze the importance of different features (words) in predicting whether an article is fake or real.

## Results:
- **Decision Tree CV Accuracy**: (Insert accuracy here)
- **Random Forest CV Accuracy**: (Insert accuracy here)

The Random Forest model generally performs better due to its ensemble nature, reducing overfitting compared to a single decision tree.

## Technologies Used:
- **Python**
- **Scikit-learn**: For implementing machine learning models and cross-validation.
- **TF-IDF**: For text feature extraction.
- **Matplotlib**: For visualization of feature importances and decision tree.
- **Graphviz**: For visualizing decision trees.

