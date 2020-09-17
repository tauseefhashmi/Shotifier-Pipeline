# Shotifier: A Binary Short Conversion Classifier Pipeline of Soccer Forwards

In this paper, we present Shotifier, a binary classification pipeline based on the principle of hybrid parallelism. Shotifier focuses on forwards or strikers and uses match statistics for classifying whether the shot from the striker at the opponent's goal converts into a goal or not. Soccer, is one of the most popular sports, is also considered unpredictable as one can expect a lot of unlikely events in every match. The characteristics of being a low scoring game emphasize the importance of the goal of winning a match. However, identifying the factors that have a substantial influence on the player’s position for converting a shot into a goal is a challenging task. Hence, to address this challenge, we have narrowed down our research and analysis on forwards or strikers, who are primarily the goal-scoring players. Shotifier is a hybrid parallelism based pipeline with two steps: (a) The Kernel Density Estimator (KDE) to visually represent high concentrated zones on the ground for specific events in the match along with identification of maximum ball activities based on observed ball's start and end position, (b) From the match statistical data, identify the features that have a strong influence on shots converting to a goal by applying Support Vector Machine (SVM), XGBoost, Random Forest, and Multi-layer Perceptron (MLP) models. Finally, k-fold cross-validation is employed to evaluate the effectiveness of the models where SVM is performing better than other model with an accuracy of 86.92$\%$.
