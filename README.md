# Twitter-Sentiment-Analysis
This project analyzes the sentiment of tweets using natural language processing techniques. The goal of this project is to classify tweets as positive, negative, or neutral, based on their content. The model was trained using a dataset of over 11,000 labeled tweets, and has an accuracy of 80%.

Take two different Datasets, one is Training Dataset which consists of Tweets along with Airline Sentiment and other one is Testing Dataset which consists of Tweets but not Airline Sentiment, and by applying NLP(Natural Language Processing) ,i.e NLTK And Sklearn Classifier, we Predict Airline Sentiment of Testing Dataset.

Performed NLP Based `Tokenization`, `Lemmatization`, `Vectorization` and processed Data in Machine Understandable Language.

#### Used 4 pre-trained Machine Learning Algorithms in order to classify Tweets:
1. Support Vector Classifier (SVC)
2. Multinomial Naive Bayes Classifier
3. Random Forest Classifier
4. Decision Tree Classifier

`Support Vector Classifier (SVC)` outperformed other algorithms with an accuracy score of 80% making it the most effective classifier in the study.

### ScreenShots:

1.Spliiting the Tweet text into words using NLTK

<img width="522" alt="image" src="https://user-images.githubusercontent.com/72342649/226348285-31d76e1a-b5bf-4bd5-becf-a6e80bd849d3.png">

2.Cleaning the Words using WordNetLemmatizer available in NLTK

<img width="516" alt="image" src="https://user-images.githubusercontent.com/72342649/226352873-24a19d0e-a6d6-4262-800b-950b55681328.png">

3.Analysing Count Vectorizer and Prepare a Frequency matrix

<img width="715" alt="image" src="https://user-images.githubusercontent.com/72342649/226348576-9a56bd16-6877-4683-aecc-b3c50dde3ffb.png">

4.Normalize the matrix obtained from Count Vectorizer through TF-IDF Transformer

<img width="726" alt="image" src="https://user-images.githubusercontent.com/72342649/226350117-57dfa71b-6faa-4d6a-9500-8dd1710a6d9a.png">

5.Using TF-IDF Vectorizer to get X train Features

<img width="687" alt="image" src="https://user-images.githubusercontent.com/72342649/226350451-47d58fda-2b87-4f3e-8c09-66d1b235c317.png">

6.Splitting Training Dataset in order to find Accuracy Score
<img width="677" alt="image" src="https://user-images.githubusercontent.com/72342649/226350824-c5a42e18-bf5f-48d8-89eb-82ce1f3ab406.png">

7.SVC (Support Vector Classifier)

<img width="466" alt="image" src="https://user-images.githubusercontent.com/72342649/226350939-be75eaf4-70dd-4bd8-9515-98877392f688.png">

8.Random Forest Classifier

<img width="466" alt="image" src="https://user-images.githubusercontent.com/72342649/226351017-a9ac69d7-1b1b-450a-9a2c-3f4ae411f2fa.png">

9.Multinomial Naive Bayes Classifier

<img width="448" alt="image" src="https://user-images.githubusercontent.com/72342649/226351200-b6d7f974-4c32-4610-ba3f-40cbe424a03b.png">

10.Decision Tree Classifier

<img width="488" alt="image" src="https://user-images.githubusercontent.com/72342649/226351294-27356c74-c91d-40f5-9243-c603fd8abedf.png">


#### Accuracy of each Classifier:
- Support Vector Classifier --> 79.052 %
- Multinomial Naive Bayes -->  76.183 %
- Random Forest Classifier --> 73.72 %
- Decision Tree Classifier --> 68.306 %

#### Among all the 4 Classifiers, which are applied SVC  predicts Result with higher Accuracy Score

