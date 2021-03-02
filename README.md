# NLP coursework code repository

## Overview
In this coursework, we have implemented different methods to predict the score for how funny the edited headline is (Task1). This readme explains how to run our code and reproduce specific results quoted in the report.

## Setup

Please make sure the following are installed:

	   !pip install torch
	   !pip install transformers
	        
## How to run different methods
The SIMPLEST way is to run all cells from top to bottom(e.g. Ctrl+Enter) for your choice of approach/method. The following subsections explains how to reproduce the quoted results in the report for specific model/approach.

### Approach 1 - Bert and Roberta
To reproduce the results for this method, please run *BERT_and_RoBERTa.ipynb* file and the model obtained the best performance for both Bert and Roberta will be shown.
### Approach 1 - BiLSTM
To reproduce the results for this method, please run *BiLSTM.ipynb* file. 

To select different preprocessing method, please locate *change preprocessing method* section and select the following:

- pre_processing(1): Replace the wordin the bracket with the edit word.  
- pre_processing(2):  Show both original sentence and the edit sentence to the net-work.  
- pre_processing(3):  Append the edit word at the end of theoriginal sentence.  
- pre_processing(4):  Append the edit word after the word needs to be replaced


### Apporach 2

To reproduce the results for this approach, please run *approach2.ipynb* file. 

To select different corpus, please locate *change number in word_corpus* section and select the following:

- word_corpus(1): original  sentence  in train, dev and test.csv.

- word_corpus(2): original  sentence  in train, dev and test.csv + additional  news  headlines.

- word_corpus(3): original  sentence  in train, dev and test.csv + additional  news  headlines + edit sentences in  train, dev and test.csv.
