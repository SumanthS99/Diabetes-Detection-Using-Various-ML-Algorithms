# Diabetes Detection Using Various ML Algorithms

This project handles diabetes prediction using a dataset of 100,000 individuals with features like age, gender, and medical history. Since only 8.5% of the cases are diabetic, the dataset is imbalanced, so choosing right evaluation metrics is crucial (can't fully rely on accuracy score).
## Approach:

### Exploring the Data: 
We start by understanding the dataset, cleaning it up, and performing basic analysis.
### Multiple ML approaches
We apply multiple machine learning algorithms, from Logistic Regression to Random Forests, to find the best fit.
### Prioritizing f1-score:
Given the dataset imbalance, our focus is on maximizing f1-score.
### Tuning and Comparing: 
We fine-tune the models, compare their performance, and choose the one that performs best in terms of recall and f1-score.
After testing various algorithms, we achieved a f1-score of 97% with the Random Forest model.

## Next Steps:
Advanced Algorithms: Experiment with more advanced models like Boosting methods or Neural Networks.

Improving Features: Perform more feature engineering to enhance model performance.
