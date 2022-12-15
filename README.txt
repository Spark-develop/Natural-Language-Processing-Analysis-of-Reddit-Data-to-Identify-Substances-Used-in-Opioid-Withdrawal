Steps to Reproduce:

[1] Install All necessary libraries like Pandas, Numpy, Matplotlib, Scikit-Learn, PyTorch, Beautiful Soup(BS4), Selenium, nltk, etc. using pip.

[2] Run opiate_Recovery.ipynb, scrap_Reddit.ipynb and scrap_Twitter.ipynb files first from the folder Webscrapping/, which will web scrap data from the sites
    and store them inside /webdata in csv format

[3] Run NER/trainNER.ipynb for training NER model and storing the trained model to the disk en_reddit_ner/en_reddit_ner.

[4] Run NER/NER_annotate.ipynb for annotating substance and effects using the trained NER model and making a final dataset(train.csv).

[5] Run Bert/data_aug.ipynb for data seperation and train data augmentation.

[6] Run Bert/bert_std.ipynb, Bert/robertbert_std.ipynb and Bert/XLNet_std.ipynb for training and predicting the remedies.

Evaulation will be available in Bert/results folder.

Thank you.