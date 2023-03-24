# scrabbing-and-sentiment

In this project I obtained data from https://www.airlinequality.com/ via scrabbing with Selenium. From Turkish airlines reviews, each pages include 100 comment I scarb and draw 25 pages and get almost 2400 reviews. I  used preparation and manupulation techniques like Regex,stopwords,etc... to get ready data to modelling. 
Moreover, You can see Bert ("distilbert-base-uncased-finetuned-sst-2-english") classification analysis, Vader Sentiment analysis and Roberta Emotion anlysis model to find customer feelings and comments about their travel experiences. On the other hand I used machine learning classification models(with compare some classifications models results and fine tuning to find best model) to compare recommends of customers with Bert and Vader sentiment analysis to evaluate this model results according to their recommendations. 
Finally You can see emotion analysis with Hugging face model("j-hartmann/emotion-english-distilroberta-base") and which emotion has most count

