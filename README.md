# fake-news-detection

## :chart_with_upwards_trend:	 Description Of The Model
### Data Preprocessing 
</br>
One of the major forms of preprocessing is to filter out useless data. In natural language processing, uninformative words are referred to as stop words. We would not want these words to take up space in our database, or expend our valuable CPU time. NLTK is employed for removal of the stop words in this project. Null values are replaced with empty string. Author name and news title is merged to improve performance. The Porter Stemmer algorithm is used for transformation of words into root words. TfidfVectorizer is used for transformation of text data into numeric data.
 </br>

### Training the Model </br>
The dataset is splitted as 80% for training set and 20% for test set. Logistic regression is used in the model.

## :newspaper:	 Dataset
https://www.kaggle.com/c/fake-news/data?select=train.csv

</br>

## :mag_right: For more...

- [NLTK](https://www.nltk.org)

- [Porter Stemming Algorithm - Basic Intro](https://vijinimallawaarachchi.com/2017/05/09/porter-stemming-algorithm/)

- [TfidfVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)
