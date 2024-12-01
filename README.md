# AI-Based Diabetes Detection

This project leverages machine learning algorithms to predict whether an individual is diabetic or non-diabetic based on symptoms and biometric data. By using **scikit-learn** for the machine learning models, the system aims to enhance the speed, accuracy, and accessibility of diabetes detection.

## Features
- **Random Forest**, **SVM**, **Decision Tree**, and **XGBoost** classifiers are used for prediction.
- Real-time prediction based on inputs such as **Glucose levels**, **Blood Pressure**, **BMI**, and **Age**.
- **Gradio** is used for an easy-to-use web interface, making the system accessible for all users.
- The system provides quick feedback on whether a user is diabetic or non-diabetic.

## Dataset
- The model uses a **Kaggle diabetes dataset** containing features like **Glucose levels**, **Blood Pressure**, **Skin Thickness**, **Insulin levels**, **BMI**, and **Age**.
- Kaggle Dataset: [Diabetes Dataset - Pima Indians](https://www.kaggle.com/datasets/nancyalaswad90/review)

## Model Accuracy
- **Random Forest**: 0.7917
- **SVM**: 0.7865
- **Decision Tree**: 0.7292
- **XGBoost**: 0.7083

## Technologies Used
- **Machine Learning Algorithms**: Random Forest, SVM, Decision Tree, XGBoost (via `scikit-learn` and `xgboost` library)
- **Frontend**: Gradio interface for easy user interaction.
- **Deployment**: Hugging Face for hosting the model and Gradio interface.

## Conclusion
This project demonstrates the potential of machine learning to enhance the accuracy, speed, and accessibility of diabetes detection. By utilizing scikit-learn’s efficient machine learning models like Random Forest, SVM, Decision Tree, and XGBoost, it enables timely, real-time predictions based on essential health parameters.
While Random Forest proved to be the most efficient for this task, the system offers a strong foundation for future integration with clinical systems and further model refinement. By providing a cost-effective, accurate, and accessible solution for early diabetes detection, this project aims to improve health outcomes through ML Algorithms.
