# NLP coursework code repository

## Overview
In this coursework, we have 

## Setup

If running Bert and Roberta.ipynb, please make sure the following are installed:

	   !pip install torch
	   !pip install transformers
	        
## How to run different methods
The SIMPLEST way is to run all cells from top to bottom(e.g. Ctrl+Enter) for your choice of approach/method.
### Approach 1 - Bert and Roberta
To reproduce the results for this method, please run *BERT_and_RoBERTa.ipynb* file and the model obtained the best performance for both Bert and Roberta will be shown.
### Approach 1 - BiLSTM
To reproduce the results for this method, please run *BiLSTM.ipynb* file
function pre_processing(method) 
change method to get different preprocessing method: 
method = 1: Replace the wordin the bracket with the edit word.  
method = 2:  Show both original sentence and the edit sentence to the net-work.  
method = 3:  Append the edit word at the end of theoriginal sentence.  
method = 4:  Append the edit word after the word needs to be replaced


### Apporach 2

To reproduce the results for this approach, please run *approach2.ipynb* file. To 
function word_corpus(method)
change method to get different corpus: 
method =  1: original  sentence  in train, dev and test.csv.   
method =  2: original  sentence  in train, dev and test.csv + additional  news  headlines.   
method =  3: original  sentence  in train, dev and test.csv + additional  news  headlines + edit sentences in  train, dev and test.csv.   
