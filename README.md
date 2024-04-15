# RLL_collapse_on_data
Current repo was created as an archive for dataset analysis which were done during the investigation on collaps eof the fine-tune data.
- In train and test original are 4 columns for subredit title label and post.
- In file match_mismatch_prediction_list. given Post, Label, Prediction, Score and Four criteria for human judgement.
- In file Match_mismatch given original posts labels for them sorted in order match /mismatch by aspect 
(Sentence length [:200]
Part of Speech [200:400]
Lemmata [400:460]
Sentiment analysis [460:660]
Topic analysis [660:]).
- In file lemma_pos_sent given preprocess data from original train and test.
- In file topics given preprocess data with use of Berttopic
