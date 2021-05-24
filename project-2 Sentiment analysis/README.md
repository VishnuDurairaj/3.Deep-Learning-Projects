
•	The dataset was collected from three different websites which are Amazon.com, imdb.com, yelp.com.

•	There were lot of unwanted characters and website urls so, I used regular expression and nltk library to clean those unwanted things from the data.

•	I used pretrained word2vec model to convert words into vectors.

•	Finally, I fed the data into GRU. And it gave more than 90% accuracy.

•	Then I build a simple web app using Django and deployed it on Heroku.

•	You try my app: https://x2sentiment.herokuapp.com
