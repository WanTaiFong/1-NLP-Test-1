NLP Test 2, Result Spreadsheet				
				
Following the tutorial of the following 1 to better know how to handle pre-processing for word data and to test effects of the different layers in the neural network				
* https://www.kaggle.com/c/word2vec-nlp-tutorial/overview/part-1-for-beginners-bag-of-words				
				
Following NLP Test 1				
* Different variants of the dense network will be tested			
* Dropout layers will be introduced			
				
				
Given 50,000 reviews, the test will use 50% validation split				
However, the other 25,000 is unlabelled and only by submitting to kaggle will the accuracy be known.				
As such, for simplicity the early testing will be done by using Training data accuracy as a gauge of fitting			
When the models are finalised, then the output files will be submitted to kaggle for marking			
				
Using a control group of:				
* Batch size of 128			
* 32-dimension vector for word embedding and 			
* Dictionary of top 5,000 words			
* Maximum of 5000 tokens per input, as the inputs are already integer encoded			
* Epochs 3			
