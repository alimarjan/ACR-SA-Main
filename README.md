# Cite this as

Kamyab M, Liu G, Rasool A, Adjeisah M. 2022. ACR-SA: attention-based deep model through two-channel CNN and Bi-RNN for sentiment analysis. PeerJ Computer Science 8:e877 https://doi.org/10.7717/peerj-cs.877

# ACR-SA: Attention-based deep model through two-channel CNN and Bi-RNN for sentiment analysis.
Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) have been successfully applied to Natural Language Processing (NLP), especially in sentiment analysis. NLP can execute numerous functions to achieve significant results through RNN and CNN. Likewise, previous research shows that RNN achieved meaningful results than CNN due to extracting long-term dependencies. Meanwhile, CNN has its advantage; it can extract high-level features using its local fixed-size context at the input level. However, integrating these advantages into one network is challenging because of overfitting in training. Another problem with such models is the consideration of all the features equally. To this end, we propose an attention-based sentiment analysis using CNN and two independent bidirectional RNN networks to address the problems mentioned above and improve sentiment knowledge. Firstly, we apply a preprocessor to enhance the data quality by correcting spelling mistakes and removing noisy content. Secondly, our model utilizes CNN with max-pooling to extract contextual features and reduce features dimensionality. Thirdly, two independent Bi-direction RNN, i.e., Long Short-Term Memory and Gated Recurrent Unit are used to capture long-term dependencies. We also applied the attention mechanism at the RNN layer output to emphasize each word's attention level. Furthermore, the Gaussian Noise and Dropout as regularization are applied to avoid the overfitting problem. Finally, we verify the model's robustness on four standard datasets. Compared with existing improvements on the most recent neural network models, the experiment results show that our model significantly outperformed the state-of-the-art models.

# Datasets.
IMDB: https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Sentiment140: http://help.sentiment140.com/for-students

US-airline : https://www.kaggle.com/crowdflower/twitter-airline-sentiment

SD4A: https://www.kaggle.com/kamyab20/sentiment-dataset-for-afghanistan-sd4a
