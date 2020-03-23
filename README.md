# Sentiment-Analysis-on-presion-text

A Bidirectional RNN method for sentiment analysis in Persian language
Sentiment analysis is the interpretation and classification of emotions (positive, negative and neutral) within text data using text analysis techniques. Natural language ambiguities and indirect sentiments within the social media text have made it hard to classify by using traditional machine learning approaches, such as support vector machines, naive Bayes, hybrid models and so on. In This project We use Bidirectional Recurrent Neural Networks (BidirectionalRNN) to perform sentiment analysis in Keras.


## The Dataset
The data file is available in the dataset folder. If you download the dataset, you will see a CSV file. The file contains 5000 records and two columns: test and label.


## The Embeddings File
We use FastText embeddings to create our feature matrix. The embeddings file that can be downloaded from this [ Kaggle link](https://fasttext.cc/docs/en/crawl-vectors.html). 

## Results


* The result of the loss function and test Accuracyet
![Image of Yaktocat](https://github.com/khaniamir/Sentiment-Analysis-on-presion-text-/blob/master/Result/Result7/Train%20and%20Test.png)


* The result of the confusion matrix


<img src="https://github.com/khaniamir/Sentiment-Analysis-on-presion-text-/blob/master/Result/Result7/confusion%20matrix2.png" width="600" height="350"   align="middle">


<img src="https://github.com/khaniamir/Sentiment-Analysis-on-presion-text-/blob/master/Result/Result7/confusion%20matrix1.png" width="600" height="350" >
