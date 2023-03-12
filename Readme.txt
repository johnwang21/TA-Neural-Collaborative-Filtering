Everything runs on colab.
USE TPU otherwise this will take EONS of GEOLOGICAL TIME

Main examples are: 
Twitch_NCF_meta.ipynb (correct answer)
Twitch_NCF_no_meta.ipynb (class activity)

I've included a sample trained model with meta.

####Notes
Data is in the Data folder. Note that 100_a.csv is the original twitch data. Its used to create metadata
train_streamID.csv is for prototyping only

Almost all code runs exclusively on: meta_train.csv and meta_test.csv

Note that NCF_meta is regularized and NCF_no_meta is not. This is because before regularization, meta data already beat unregularized data so I didnt bother to regularize the no meta as it would perform worse.

References:
1. Source of truth:
https://arxiv.org/pdf/1708.05031.pdf
https://github.com/hexiangnan/neural_collaborative_filtering/
