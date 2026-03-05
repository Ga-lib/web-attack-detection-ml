# web-attack-detection-ml
A ML based cybersecurity system designed to detect and classify web attacks. This project utilizes a Multi-Output Classifier to simultaneously identify the specific attack type (7 classes) and the binary status (Safe vs. Malicious).


Features implementations of Decision Trees, Random Forests, and Naive Bayes, with extensive hyperparameter tuning and evaluation metrics.

High Accuracy: Decision Tree and Random Forest models both achieved over 99% accuracy on the test set for both Attack Type and Binary Status.

Effective Tuning: I performed a deep hyperparameter grid search (taking over 2 hours) which optimized the Decision Tree to a very high level of precision.

Robust Evaluation: I generated Classification Reports and Confusion Matrices for both targets. This proves that model handles different types of attacks (like SQL Injection or Cross-Site Scripting) effectively, not just the "Safe" class.

Advanced Technique: Using a MultiOutputClassifier is a sophisticated choice. It allows one model training session to solve two different problems at once, which is a very efficient and professional approach to machine learning.
