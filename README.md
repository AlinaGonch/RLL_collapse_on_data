# RLL_collapse_on_data
The current repo was created as an archive for dataset analysis which was done during the investigation of the collapse of the fine-tuned data.
- In  the test original are 4 columns for subredit title label and post.
- In file match_mismatch_list. given Post, Label, Prediction, Score, and Four criteria for human judgment.
- In file Match_mismatch_list  sorted to match /mismatch by aspect 
(Sentence length [:200]
Part of Speech [200:400]
Lemmata [400:460]
Sentiment analysis [460:660]
Topic analysis [660:]).
- In file test_lemma_pos_sent given preprocess data from the original test.
- In file df_test_new_roberta given sentiment analysis on test data
- In file test_topic_modeling given preprocess data with the use of Berttopic
- If u need preprocessed data for train they can be downloaded on this [link](https://drive.google.com/drive/folders/1jsLW6FrrNp5eyZK3Vqs4Grjp9xz4cEj-?usp=sharing)
For 9 CP:
- In file concat_train_test_1700_rewards a collection of randomly selected 850 sentences for the  train set and 850 sentences for the test set with predictions and reward 
