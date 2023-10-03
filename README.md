# survival-prediction
Developed a classification algorithm to determine passengers that were most likely to survive the Titanic crash

In this project, the Titanic dataset obtained from Kaggle was employed to build a predictive model using the Random Forest classification algorithm. The goal was to determine which passengers were most likely to survive the Titanic crash based on various features available in the dataset.

Upon training and evaluating the Random Forest model, the results were remarkably impressive. The accuracy, precision, recall, and F1 score, all important metrics in classification tasks, achieved a perfect score of 1.0. 

An accuracy score of 1.0 implies that the model correctly predicted all survival outcomes, indicating a flawless performance. The precision score of 1.0 indicates that all positive predictions made by the model were accurate, without any false positives. Similarly, the recall score of 1.0 signifies that the model successfully identified all actual positive cases, without any false negatives. The F1-score of 1.0, which is the harmonic mean of precision and recall, also attests to the model's exceptional performance.

In summary, this project demonstrates the Random Forest model's ability to accurately predict survival outcomes for Titanic passengers, achieving a perfect score across all evaluation metrics. These results underscore the effectiveness of the machine learning approach in identifying patterns within the dataset and making highly accurate predictions regarding passenger survival during the Titanic crash.

It's important to note that while the Random Forest model achieved perfect accuracy, there is a possibility that this high accuracy could be attributed to overfitting. Overfitting occurs when a model learns the training data too well, capturing noise and specific patterns that may not generalize well to unseen data. In this case, the model might have memorized the training data, leading to exceptional performance on the dataset it was trained on but potentially hindering its ability to accurately predict outcomes on new, unseen data. Therefore, the perfect accuracy achieved should be interpreted with caution, considering the potential influence of overfitting.
