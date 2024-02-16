### This repository contains a Jupyter notebook with fine-tuning BERT for fake news classification

Weights for a base BERT model were loaded from HuggingFace Transformers, as well as the tokenizer. 
Trained for 5 epochs on a 16' MacbookPro with M1 Pro. 


##### Results:
All of the precision, recall, and F1 score averaged at 87%, with 86% being a worst result.
sklearn classification report screenshot:
![classification_report](https://github.com/everypidigit/Faker/blob/main/supplementary/classification_report.png)

##### Losses:
![losses](https://github.com/everypidigit/Faker/blob/main/supplementary/losses.png)

