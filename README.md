# DATA MINING
##Introduction: 
	Data mining is a technique of extraction hidden patterns from large data bases. 
#Sentiment Analysis
##Project outline: 
The outline of the project is sentiment identification system using Machine learning technique to classify the polarity of the movie review as positive, negative.
##Problem:
Problem is to find the polarities (sentiments) based on the reviews of the users, whether they are positive or negative (good or bad). 
##Data:
Data is obtained from tweets and imdb. The data in tweets is raw and contains unwanted numeric and special characters, they are removed in the code before performing the analysis.
#NA�VE BAYES TECHNIQUE
Bayes theorem provides a way of calculating the posterior probability, P(c|x), from P(c), P(x), and P(x|c). Naive Bayes classifier assume that the effect of the value of a predictor (x) on a given class (c) is independent of the values of other predictors. This assumption is called as class conditional independence.

	##Na�ve Bayes rule

	P(c|x)=P(x1|c)  P(x2|c) �.. P(xn|c) P(c)

�	P(c|x) is the posterior probability of class (target) given predictor(attribute).
�	P(c) is the prior probability of class.
�	P(x|c) is the likelihood which is the probability of predictor given class.
�	P(x) is the prior probability of predictor.


###Na�ve Bayes Conditional Independence Assumption

Assume that the probability of observing the conjunction of attributes is equal to the product of the individual probability P(Xi|Cj).
                                        
                                      tweet
                                   /  |  \  \          w=word
                                  /   |   \  \         c=class
                                 w1   w2   w3 w4

	Features detect term presence and are independent of each other given the class P(W1,��.W4|C) =P(W1|C)*P(W2|C)*��.P(W4|C)

This model is appropriate for binary variables. Zero probabilities cannot conditioned away, no matter the other evidence
Here Tweet representing the sentence and w1, w2, w3, w4 are representing words. Probability of the tweet is equal to the product of the probabilities of the words. Probability of each word in the each sentence is found using the posterior probability.
Thus each sentence probability will be found accordingly with the multiplication of each word probability.







