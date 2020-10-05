The goal of this project is to design a classifier to use for sentiment analysis of 
product reviews. Our training set consists of reviews written by Amazon customers for 
various food products.The reviews, originally given on a 5 point scale, have been 
adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.

In order to automatically analyze reviews, you will need to complete the following tasks:

	- Implement and compare three types of linear classifiers: the perceptron algorithm, 
	the average perceptron algorithm, and the Pegasos algorithm.

	- Use your classifiers on the food review dataset, using some simple text features.

	- Experiment with additional features and explore their impact on classifier performance.


The first part was the implementation of a linear classifier using the following functions: 
- Hinge loss function
- Perceptron algorithm
- Average perceptron algorithm
- Pegasos algorithl

The second part was the building of the automative review analyzer using a text-based features and
the linear classifiers implemented in the first part.
The text reviews are converted in feature vectors using a "bag of words" approach. We start by 
compiling all the words that appear in a training set of reviews into a dictionary , thereby 
producing a list of  d  unique words.
