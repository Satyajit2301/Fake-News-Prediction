# Fake-News-Prediction
In this project, we explore fake news detection using a logistic regression classifier. The model is trained on a labeled dataset containing real and fake news headlines and body text. We apply techniques like text cleaning, stopword removal, and TF-IDF vectorization to prepare the data for effective binary classification.

## 📂 Dataset Features
- `id`: Unique identifier for each article
- `title`: Article headline
- `author`: Author name
- `text`: Body of the article
- `label`: 0 = Real, 1 = Fake

## 🧪 Techniques Used
- Data preprocessing and cleaning
- Stemming using NLTK
- Stopword removal
- Feature extraction using TF-IDF
- Logistic Regression model

## 🔍 Evaluation
Accuracy was used to evaluate performance on the validation set.

## 🚀 What’s Next
- Add EDA visualizations (label counts, most common words)
- Try more complex models (SVM, Random Forest, LSTM)
- Hyperparameter tuning

## 👨‍💻 Run the Notebook
Simply open the `.ipynb` file and run each cell sequentially.
