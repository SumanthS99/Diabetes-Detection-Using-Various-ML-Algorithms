# Diabetes Detection Using Various ML Algorithms

This project handles diabetes prediction using a dataset of 100,000 individuals with features like age, gender, and medical history. Since only 8.5% of the cases are diabetic, the dataset is imbalanced, so getting the evaluation metrics right is crucial (can't fully rely on accuracy score). The goal here is to achieve a high recall score to catch as many diabetic cases as possible.

## Approach:

### Exploring the Data: 
We start by understanding the dataset, cleaning it up, and performing basic analysis.
### Multiple ML approaches
We apply multiple machine learning algorithms, from Logistic Regression to Random Forests, to find the best fit.
### Prioritizing Recall:
Given the dataset imbalance, our focus is on maximizing recall—minimizing the number of missed diabetic cases.
### Tuning and Comparing: 
We fine-tune the models, compare their performance, and choose the one that performs best in terms of recall.
After testing various algorithms, we achieved a recall of 97% with the best-performing model.
### Next Steps:

Advanced Algorithms: Experiment with more sophisticated models like Gradient Boosting or Neural Networks.

Improving Features: Perform more feature engineering to enhance model performance.
