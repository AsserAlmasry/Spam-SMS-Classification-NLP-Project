# Spam-SMS-Classification-NLP-Project

Classifying SMS messages as spam or not, helps in filtering and cleaning the SMS from the phone.


The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged according being ham (legitimate) or spam.

Project Overview:

•	Classifying SMS messages as spam or not (often called “ham”) is a common task in natural language processing (NLP).
•	Created a machine learning model that detects and classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing.
•	Engineered features like word count, contains currency symbol, and contains number from the text SMS. 

➢ Resources Used:

•	Packages: pandas, numpy, sklearn, matplotlib, seaborn, nltk.
•	Dataset: The project utilizes a dataset consisting of labeled SMS messages, with each message categorized as either spam or ham. The dataset is split into training and testing sets to train the classifier and evaluate its performance.
•	Dataset by UCI Machine Learning on Kaggle: 
SMS Spam Collection Dataset (kaggle.com)
•	The original dataset:
SMS Spam Collection - UCI Machine Learning Repository

➢ Text (data) Preprocessing:

•	Tokenization: Breaking down the SMS text into individual words or tokens.
•	Lowercasing: Converting all text to lowercase to maintain consistency.
•	 Eliminating punctuation marks as they typically do not contribute to meaning.
•	Stop-word Removal: Removing common words like "and," "the," etc., which may not be helpful for classification.
•	Lemmatization: Reducing words to their base or root form (e.g., "running" to "run") to treat similar words uniformly.

