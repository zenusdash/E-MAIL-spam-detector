# E-MAIL-spam-detector
 🔍 Problem Statement

Spam emails are a major challenge in digital communication, often including scams, phishing attempts, or irrelevant content. This project aims to develop an efficient and scalable solution that can automatically detect and filter spam emails from legitimate ones.

### ✅ Key Features

* Text preprocessing: cleaning, tokenization, stopword removal, and stemming
* Feature extraction using **TF-IDF Vectorization**
* Model training using:

  * **Multinomial Naive Bayes**
  * **Logistic Regression**
  * **Support Vector Machine (SVM)**
* Performance evaluation with accuracy, precision, recall, and F1-score
* Confusion matrix visualization
* Final model export using `joblib` for deployment

### 🛠️ Technologies Used

* Python, Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn (`sklearn`)
* Natural Language Toolkit (`nltk`)
* Jupyter Notebook / Google Colab

 📈 Results
Achieved **over 98% accuracy** with the Naive Bayes model. The model is robust and generalizes well to unseen data.
 
 🚀 Future Scope

* Deploy the model in a web application or email client
* Use deep learning models like LSTM or BERT for improved context understanding
* Real-time spam filtering integration
* Adaptive learning from new types of spam messages

---

