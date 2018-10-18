# Waton-Assistant-Testing-Tools
collection of Jupyter Notebook in Python that can be used to test your Watson Assistant workspace

## Performance Testing 
This notebook can be used for Regression testing and Blind testing. 

1. **Regression Test Scope**: This can be used to test a set of testing phrases that are not part of the training set in Watson Assistant (WA). The idea is that you would re-run this test over time after the improvement phase, to check the health status of your workspace, and make sure that the workspace is still behaving in a consistent manner. 
2. **Blind Test Scope**: Simply analyse a set of testing phrases that are not part of the training set in Watson Assistant. This can be a one-off task requested by stakeholders. 


## K-Fold Cross Validation 
This notebook will allow the user to perform a K-fold cross validation test on your Watson Assistant workspace 


## Optimal Threshold Analysis 
This notebook can be used to search for the optimal value of the confidence level threshold to use in your Waston Assistant workspace.

## N-Gram Testing 
This notebook will be used for diagnosis of incorrect intent detection problem. We want to use unigrams, bigrams and trigrams to do so.

The idea is that each intent is sensitive to particular words/combination of words. The scope is to find a fast way to detect why, for instance, a testing phrase didn't trigger the right intent.This notebook will help the user understanding why which words and in which positions are the most important in the intent detection phase. 
