# imdb-sentiment-analysis
Sentiment analysis on IMDb movie reviews using traditional Machine Learning algorithms

The app uses the IMDb reviews dataset that can be found [here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). It contains 50.000 reviews classified as `positive` or `negative`. 

Algorithms used:
- Support Vector Machines
- Multinomial Naive Bayes
- Gaussian Naive Bayes
- K-Nearest Neighbors

### Preprocessing of Data
Preprocessing consists of the following steps:
1. Removal of HTML tags in the text
2. Removal of stopwords
3. Token lemmatization
4. Removal of anything that is not a letter or number using regex
5. Token decapitalization

## Results of running the App
#### SVM<br>
<img src=https://github.com/ConSpd/imdb-sentiment-analysis/assets/74179715/c1f11799-2e3d-469c-8f37-b682a08c6776 width=300><br><br>
---

#### KNN<br>
<img src=https://github.com/ConSpd/imdb-sentiment-analysis/assets/74179715/7e1c9083-b6a2-48f6-b89e-5c78e3d7c678 width=300><br><br>
---

#### Gaussian Naive Bayes<br>
<img src=https://github.com/ConSpd/imdb-sentiment-analysis/assets/74179715/fd22c294-6e3a-4add-ba9d-bd3ad5b0a1dd width=300><br><br>
---

#### Multinomial Naive Bayes <br>
<img src=https://github.com/ConSpd/imdb-sentiment-analysis/assets/74179715/7dc7acc4-fb11-41d0-a0d1-1eda33bb3cce width=300><br>
