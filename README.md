# Log Message Readability (ASE 2023)

This is the repository of the replication package for our ASE 2023 paper "[Are They All Good? Studying Practitioners' Expectations on the Readability of Log Messages](https://github.com/ginolzh/ginolzh.github.io/blob/main/papers/ASE2023_Log_Message_Readability.pdf)".

- `interview` contains our interview guidelines
- `manual` contains our manually labelled log messages
- `survey` contains the design of our survey questions and the statistics of the survey data
- `classify` contains the code for the classifiers


To run the classifier, please check `classify.py` and specify the aspect to classify (line 50) and the algorithm (line 53)

Then run the following command:

`python classify.py`
