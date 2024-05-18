This is my repo for the solving the assignment for joining the AI Community of IIT Bombay.


Q1) The question was about fine tuning a pretrained model on a dataset for object detection.
    I have used Tensorflow framework for it
    I have used Pascal voc 2007 dataset for it
I have used for VGG16 pretrained model for fine tuning
on top of VGG16, i performed Average Pool (to reduce parameters and prevent overfitting), Max pool would have been better option as well. I then introduced two fully connected layers of 1024 and 512 neurons respectively.
I then unfreezed the last 4 layers of the model. This allows efficient fine tuning and better extraction of features.


Q1)Bonus 
I figured about Vision transformers. 
I read the research paper "Attention is All You Need"                       https://arxiv.org/pdf/1706.03762
                      and "AN IMAGE IS WORTH 16X16 WORDS"                   https://arxiv.org/pdf/2010.11929


Q2) The question was to make a chatbot using RAG and attention mechanism
I tried to implement a very basic architecture


Q3) I tried to understand the maths behind Deep Learning.
    I learnt about various metrics for calculating distances like Manhattan, Chebyshev,
    Minkowski, Hamming, Kullback Leibler Divergence, Hausdorff distance, Dynamic Time Warping, Frechet Distance

I learnt why euclidean distance fail in higher dimensional space.
I then generated a corpus of words and then find there vector embeddings and plotted them
I also calculated their cosine similarity
