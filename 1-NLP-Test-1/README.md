#NLP Test 1

Following the tutorial of the following 2 and combining the methods to better understand the parameters and different approaches.		
* https://colab.research.google.com/github/Hvass-Labs/TensorFlow-Tutorials/blob/master/20_Natural_Language_Processing.ipynb#scrollTo=rs3zCb_v5HfZ		
* https://machinelearningmastery.com/predict-sentiment-movie-reviews-using-deep-learning/		
		
Sentimental Analysis using Keras imported IMDb, most likely archived data.		

Given 100,000 reviews, the test will use 50% validation split		

There are 88,585 unique words in this sample group and are already tokenised into numerical values		



Using a control group of:		
* Batch size of 128	
* 32-dimension vector for word embedding and 	
* Dictionary of top 5,000 words	
* Maximum of 500 tokens per input	
* Epochs 2	(Apparently it is very easy to overfit given the small amount of data, therefore only 2 is used here)
