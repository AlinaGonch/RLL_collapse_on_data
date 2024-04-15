# RLL_collapse_on_data
The current repo was created as an archive for dataset analysis which was done during the investigation on the collapse of the fine-tuned data.
- In  the test original are 4 columns for subredit title label and post.
- In file match_mismatch_prediction_list. given Post, Label, Prediction, Score, and Four criteria for human judgment.
- In file Match_mismatch given original posts labels for them sorted in order to match /mismatch by aspect 
(Sentence length [:200]
Part of Speech [200:400]
Lemmata [400:460]
Sentiment analysis [460:660]
Topic analysis [660:]).
- In file lemma_pos_sent given preprocess data from the original test.
- In file topics given preprocess data with the use of Berttopic
