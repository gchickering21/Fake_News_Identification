# Fake_News_Identification

One of the biggest issues facing society today is the increasing prevalence of fake news that can be found all across social media and across the internet. It is getting harder and harder to discern between what is real and what is fake, and it leaves people either questioning the truth and scientific knowledge or outright believing things that are not true. With the large amounts of fake news article that are already pervasive on the internet, the recent developments in machine learning appear to be one of the best ways to identify fake news sources and prevent them from spreading and further eroding people’s confidence in what is true.I first start by creating a wordcloud of the top 500 words found in both the fake news articles and real news articles, just to get a high level understanding of what some of the key words might be when trying to detect real vs fake news. The second task I take on is applying preprocessing techniques to clean the text, removing stop words, and applying techniques such as stemming and lemmanization, which will later prove useful in building the models themselves. After getting every text article cleaned up, I then try out two different types of models, Logistic Regression and a LSTM Recurrent Neural Network model, to see which can ultimately do better on this specific task.

To view the final file see [Fake-News-Identifier.ipynb](https://github.com/gchickering21/Fake_News_Identification/blob/main/Fake-News-Identifier.ipynb)

## Downloading Data

The data for this project was too large to store in github but can be found and downloaded from here https://www.kaggle.com/c/fake-news/data
