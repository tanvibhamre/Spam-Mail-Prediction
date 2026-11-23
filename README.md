# Spam Mail Prediction Using Machine Learning

## 1. Project Description
This project uses Machine Learning to classify email or SMS messages as Spam or Ham (legitimate messages).

The project uses Logistic Regression to predict whether a message is spam or genuine.

## 2. Objective
The main objective is to build a machine learning model that can identify unwanted spam messages and help users distinguish them from legitimate messages.

## 3. Dataset
The project uses a dataset named `mail_data.csv`.

- Total messages: 5,572
- Ham messages: 4,825
- Spam messages: 747

## 4. Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn

## 5. Project Steps
1. Importing the required libraries.
2. Loading and checking the dataset.
3. Handling missing values.
4. Converting spam and ham labels into numerical values.
5. Splitting the dataset into training and testing data.
6. Converting text messages into numerical features using TF-IDF.
7. Training a Logistic Regression model.
8. Evaluating the original model.
9. Improving the model using class weights.
10. Testing the final prediction system.

## 6. Model Results

| Model | Test Accuracy |
|---|---:|
| Original Logistic Regression | 96.68% |
| Improved Logistic Regression | 98.12% |

The improved model achieved better spam detection performance on the test dataset.

## 7. How to Run the Project
1. Download or clone this project from GitHub.
2. Open `Spam_Mail_Prediction.ipynb` in Google Colab.
3. Upload `mail_data.csv` to the Colab session.
4. Run the notebook cells in order.
5. Test the prediction system using a sample message.

## 8. Conclusion
This project demonstrates how Machine Learning can be used to classify messages as spam or legitimate. The improved Logistic Regression model achieved 98.12% test accuracy.

## 9. Future Scope
- Use a larger and more diverse dataset.
- Try other machine learning algorithms.
- Develop a simple web application for spam detection.
