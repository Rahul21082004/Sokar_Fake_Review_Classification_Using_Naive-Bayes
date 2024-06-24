# Sokar_Fake_Review_Classification_Using_Naive-Bayes
Certainly! Here's an explanation you can include in your GitHub repo readme file to describe the purpose and structure of the provided code:

---

## Fake Review Classification using Naive Bayes

### Overview:
This repository contains code to classify fake and genuine reviews using the Naive Bayes classifier. The code utilizes the scikit-learn library for text preprocessing, model training, and evaluation.

### Dataset:
The dataset used for training and testing the classifier is obtained from [insert source or description of the dataset]. It contains reviews along with their corresponding labels indicating whether they are fake or genuine.

### Code Structure:
- **Data Loading and Preprocessing**: The code first loads the dataset from a TSV file and performs basic data preprocessing steps such as removing NaN values and dropping unnecessary columns.
- **Feature Engineering**: It then extracts features from the text data using the CountVectorizer, which converts text into numerical features.
- **Model Training**: The Multinomial Naive Bayes classifier is trained on the preprocessed data. Both random oversampling and SMOTE oversampling techniques are applied to handle the imbalanced dataset.
- **Model Evaluation**: The trained model is evaluated using various metrics such as accuracy, classification report, ROC-AUC score, and confusion matrix.

### Usage:
1. Clone the repository to your local machine.
2. Install the required dependencies using pip: `pip install -r requirements.txt`.
3. Run the `fake_review_classification.py` script to train and evaluate the Naive Bayes classifier.
4. Adjust the hyperparameters and preprocessing steps as needed for experimentation.

### Results:
The classification report, ROC-AUC score, and confusion matrix are provided to evaluate the performance of the trained model. Additionally, the code identifies the most common words for fake and genuine reviews.

### Contributors:
- [Vignesh Pandiya]

Feel free to customize the content based on your specific dataset, objectives, and preferences. Let me know if you need further assistance or clarification!
