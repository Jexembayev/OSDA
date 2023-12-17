# OSDA
In the file 'Big Homework', a report on the completed work is written.




![Image alt](https://github.com/Jexembayev/OSDA/blob/main/download%20(11).png)

Based on the provided data and visualization of the results, we can draw the following conclusions about the performance of the FCA neural network compared to other machine learning models:

*"Iris" Dataset (Balanced)*

FCA exhibited perfect results on the "Iris" dataset with Accuracy, F1 Score, and ROC-AUC all at 1.0. This indicates that FCA perfectly classified samples in this balanced dataset.
In comparison, other machine learning models also showed high performance on this dataset, but FCA stands out with its perfect accuracy.

*"Stroke" Dataset (Imbalanced)*

On the imbalanced "Stroke" dataset, FCA showed significantly worse results compared to the "Iris" dataset, with Accuracy at 0.757, F1 Score at 0.198, and ROC-AUC at 0.686. These results point to issues with accuracy and detecting positive cases in an imbalanced class setting.
Compared to other models, FCA showed below-average results on the "Stroke" dataset, highlighting its limitations in dealing with imbalanced data.

*"Airline Satisfaction" Dataset (Balanced)*

On the "Airline Satisfaction" dataset, FCA showed good results with Accuracy at 0.900, F1 Score at 0.883, and ROC-AUC at 0.896, indicating a strong ability to classify in balanced data conditions.
Compared to other models, FCA demonstrates comparable results, suggesting its competitiveness on balanced data.
Overall Conclusion
FCA excels in balanced datasets, demonstrating exceptional results, but its performance diminishes in imbalanced data, as seen in the "Stroke" dataset.
This underscores the importance of considering class balance when using FCA and the need for additional strategies to enhance performance in imbalanced data settings.


_Bin_DF (3).ipynb_
This notebook details the binarization process for machine learning data, covering data preprocessing and feature engineering for binary format conversion.

_NeuralFCA (3).ipynb_
This notebook demonstrates the implementation and evaluation of a Neural FCA model, highlighting its architecture, training process, and performance on various datasets.

_Baseline(1).ipynb_
This notebook compares baseline machine learning models like Decision Trees and Logistic Regression against the Neural FCA model, focusing on implementation and performance evaluation.
