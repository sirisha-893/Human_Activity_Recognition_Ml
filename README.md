Human Activity Recognition using Machine Learning
Overview
In this project, I built a system to recognize human activities like Walking, Sitting, and Standing by analyzing smartphone sensor data. I focused on comparing different Machine Learning models to find which one predicts activities most accurately.
What I did in this project:
Data Exploration: I analyzed the importance of Accelerometer and Gyroscope sensors and checked how different volunteers contributed to the dataset.
Dimensionality Reduction: Since the data had 561 features, I used PCA (Principal Component Analysis) to keep 99% of the information while reducing the number of features. I also used t-SNE to visualize how different activities form separate groups.
Model Comparison: I didn't just use one model. I trained and tested several algorithms to compare their results:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier (This gave better stability)
K-Neighbors Classifier (KNN)
Evaluation: For each model, I generated a Confusion Matrix to see where the model was making mistakes (like confusing Sitting with Standing).
Results & Insights:
I found that Dynamic activities (like Walking) are easier for the model to identify than Static activities (like Sitting).
Using Random Forest helped in reducing errors that I saw in a single Decision Tree.
Feature scaling was crucial for models like KNN to perform well.
Tech Stack:
Language: Python
Tools: Google Colab, Scikit-learn, Pandas, Matplotlib, Seaborn.
