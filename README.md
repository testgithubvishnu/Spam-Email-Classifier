This project is a Spam Email Classifier that uses a Naive Bayes classifier to detect whether an email message is spam or ham (non-spam). The classifier is trained using the scikit-learn library and processes textual data using the CountVectorizer for feature extraction.

🚀 Features
Classification of emails as spam or ham.
Naive Bayes Model for efficient and effective spam detection.
Text Preprocessing with CountVectorizer.
Performance Evaluation with metrics like accuracy score, confusion matrix, and classification report.

🗂️ Dataset
The dataset is a CSV file containing two columns:

class: Label indicating whether the message is spam (1) or ham (0).
message: The content of the email or message.

🧪 How it Works
Data Splitting: The dataset is split into training and testing sets.
Text Vectorization: CountVectorizer converts the email messages into a numerical format.
Model Training: A Multinomial Naive Bayes model is trained on the vectorized data.
Evaluation: The model is evaluated on the test set using accuracy, precision, recall, and F1 score.
