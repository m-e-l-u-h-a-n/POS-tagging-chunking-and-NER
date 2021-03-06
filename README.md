## PART OF SPEECH TAGGING:
POS tagging is a task of labelling each word in a sentence with its appropriate part of speech that includes nouns, verb, adverbs, adjectives, pronouns, conjunction and their sub-categories.Most of the POS tagging falls under Rule Base POS tagging, Stochastic POS tagging and Transformation based tagging. In this lab task , I used the CRF++ tool over a certain piece of training data and 3 different templates(feature)files , to analyse the difference in the accuracy obtained over a piece of testing data.

Following are the results obtained from using three different templates each having diffrent features. These are overall performances of model and detailed performance of the model is contained in the `accuracy.txt` file in the corresponding folders.

###### TEMPLATE 1 (Available in the POS_1 folder) following are the observations obtained:
- **accuracy:**  91.92%; **precision:**  91.92%; **recall:** 91.92%; **FB1:**  91.92
###### TEMPLATE 2 (Available in the POS_2 folder) following are the observations obtained:
- **accuracy:**  94.98%; **precision:**  94.98%; **recall:**  94.98%; **FB1:**  94.98
###### TEMPLATE 3 (Available in the POS_3 folder) following are the observations obtained:
- **accuracy:**  93.34%; **precision:**  93.34%; **recall:**  93.34%; **FB1:**  93.34

**Conclusion:**
After repeating the experiment on three different model and going through the accuracy.txt obtained after testing each experiment I got concluded following points:
- Time taken to train the model depends on the number of features we define on template used.
- Our datas for both training and testing should be significant in terms of size.
- More features in most general cases can incerease both time required for training as well as accuracy. So it has both positive nad negative sides but positive side obviously has higher weight here.

## Chunking:
Chunking is a process of extracting phrases from unstructured text, which means analyzing a sentence to identify the constituents(Noun Groups, Verbs, verb groups, etc.) However, it does not specify their internal structure, nor their role in the main sentence.
It works on top of POS tagging. It uses POS-tags as input and provides chunks as output. In this lab task , I used the CRF++ tool over a certain piece of training data and 3 different templates(feature)files , to analyse the difference in the accuracy obtained over a piece of testing data.
Following are the results obtained from using three different templates each having diffrent features. These are overall performances of model and detailed performance of the model is contained in the `accuracy.txt` file in the corresponding folders.

###### TEMPLATE 1 (Available in the ner_1 folder) following are the overall observations obtained:
- **accuracy:**  91.92%; **precision:**  91.92%; **recall:** 91.92%; **FB1:**  91.92
###### TEMPLATE 2 (Available in the ner_2 folder) following are the overall observations obtained:
- **accuracy:**  94.98%; **precision:**  94.98%; **recall:**  94.98%; **FB1:**  94.98
###### TEMPLATE 3 (Available in the ner_3 folder) following are the overall observations obtained:
- **accuracy:**  93.34%; **precision:**  93.34%; **recall:**  93.34%; **FB1:**  93.34

**Conclusion:**
After repeating the experiment on three different model and going through the accuracy.txt obtained after testing each experiment I got concluded following points:
- Time taken to train the model depends on the number of features we define on template used.
- Our datas for both training and testing should be significant in terms of size.
- More features in most general cases can incerease both time required for training as well as accuracy. So it has both positive nad negative sides but positive side obviously has higher weight here.


## NAMED ENTITY RECOGNITION:
Sometimes referred to as entity chunking, extraction, or identification — is the task of identifying and categorizing key information (entities) in text. In this lab task , I have used the CRF++ tool over a certain piece of training data and 3 different templates(feature)
files , to analyse the difference in the accuracy obtained over a piece of testing data.
Following are the results obtained from using three different templates each having diffrent features. These are overall performances of model and detailed performance of the model is contained in the `accuracy.txt` file in the corresponding folders.

###### TEMPLATE 1 (Available in the ner_1 folder) following are the overall observations obtained:
- **accuracy:**  91.92%; **precision:**  91.92%; **recall:** 91.92%; **FB1:**  91.92
###### TEMPLATE 2 (Available in the ner_2 folder) following are the overall observations obtained:
- **accuracy:**  94.98%; **precision:**  94.98%; **recall:**  94.98%; **FB1:**  94.98
###### TEMPLATE 3 (Available in the ner_3 folder) following are the overall observations obtained:
- **accuracy:**  93.34%; **precision:**  93.34%; **recall:**  93.34%; **FB1:**  93.34

**Conclusion:**
After repeating the experiment on three different model and going through the accuracy.txt obtained after testing each experiment I got concluded following points:
- Time taken to train the model depends on the number of features we define on template used.
- Our datas for both training and testing should be significant in terms of size.
- More features in most general cases can incerease both time required for training as well as accuracy. So it has both positive nad negative sides but positive side obviously has higher weight here.
