# suggestion-detection
This work involves feature engineering, training and evaluating a classifier/combination of classifiers for suggestion detection, using the data from SemEval-2019 Task 9 subtask A to classify whether a piece of text contains a suggestion or not.  The CSV file contains a header row followed by 6,100 rows spread across 3 columns of data. Each row of data contains a unique id, a piece of text and a label assigned by an annotator. A label of 1 indicates that the given text contains a suggestion while a label of $0$ indicates that the text does not contain a suggestion. Further details about the task and dataset at (https://aclanthology.org/S19-2151/) and https://github.com/Semeval2019Task9?tab=repositories

In this notebook, an analysis on pre-processing, kinds of features that can be used and performance of models is done. 
