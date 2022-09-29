# fake-news-detection

## :chart_with_upwards_trend:	 Description Of The Model
### Data Preprocessing </br>
One of the major forms of preprocessing is to filter out useless data.  In natural language processing, useless words, are referred to as stop words.We would not want these words to take up space in our database, or taking up valuable processing time.  NLTK was used for this, and the stop words were removed.  Null values replaced with empty string. Author name and news title merged to improve performance. the Porter Stemmer algorithm was used to reduce the word to the root word. TfidfVectorizer was used to convert text data to numeric data. </br>

### Training the Model </br>
The dataset is splitted as 20% test 80% training. Logistic regression was used in the model.

## :newspaper:	 Dataset
https://www.kaggle.com/c/fake-news/data?select=train.csv

</br>

## :mag_right: For more...

- [NLTK](https://www.nltk.org)

- [Porter Stemming Algorithm - Basic Intro](https://vijinimallawaarachchi.com/2017/05/09/porter-stemming-algorithm/)

- [TfidfVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)
