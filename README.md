# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ABHISHEK S LAMANI

*INTERN ID*: CT04DM681

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH 

# TASK DESCRIPTION

 Machine Learning Model Implementation – Spam Email Detection
Objective
The objective of this task is to develop a predictive machine learning model using Scikit-learn that can automatically classify text messages as either spam or ham (not spam). This task demonstrates how to build, train, and evaluate a classification model based on natural language text data.

Dataset
For this implementation, we use the SMS Spam Collection Dataset, which consists of over 5,000 text messages labeled as either "spam" or "ham." The dataset is publicly available and commonly used in text classification tasks. Each entry includes a message and its corresponding label.

Tools and Libraries
The implementation is done in a Jupyter Notebook using the following Python libraries:

pandas for data handling

scikit-learn (sklearn) for model development

TfidfVectorizer for converting text to numerical features

MultinomialNB for building a Naive Bayes classification model

matplotlib and seaborn for visualization

Methodology
Data Loading and Preprocessing
The dataset is loaded into a pandas DataFrame, and the text labels ("spam" and "ham") are encoded into binary values (1 for spam, 0 for ham). This binary classification is necessary for supervised learning.

Text Vectorization
Since machine learning models cannot process raw text, the messages are transformed into numerical format using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This technique helps quantify the importance of words in a message relative to the entire dataset.

Train-Test Split
The data is divided into training and testing sets using an 80-20 split. The training set is used to teach the model, while the testing set evaluates its performance on unseen data.

Model Training
A Multinomial Naive Bayes classifier is trained on the vectorized text data. Naive Bayes is well-suited for text classification due to its efficiency and effectiveness in handling word probabilities.

Evaluation
The model's performance is evaluated using accuracy score, confusion matrix, and classification report (which includes precision, recall, and F1-score). A heatmap of the confusion matrix is also displayed for visual interpretation.

Outcome
The final model is able to predict whether a message is spam or ham with high accuracy. This task provides hands-on experience in:

Text preprocessing

Feature extraction from text data

Building a machine learning classification model

Evaluating model performance

This task illustrates the end-to-end workflow of creating a machine learning model for spam detection using Scikit-learn. It showcases essential steps in text classification and provides a foundation for more advanced natural language processing (NLP) projects.

# OUTPUT

![Image](https://github.com/user-attachments/assets/e0fe8f06-df9f-44ca-a5b7-3e0a854b5037)
![Image](https://github.com/user-attachments/assets/bfa44549-8987-4afc-9e02-5c89f81d6047)
![Image](https://github.com/user-attachments/assets/58091fd2-e7a6-4249-9eba-880c6b83c04e)
![Image](https://github.com/user-attachments/assets/06a9fabc-b7a2-4c34-b0ec-136c8de7a564)

