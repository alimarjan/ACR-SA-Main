# Marjan Kamyab, Guohua Liu,Michael Adjeisah, Abdur Rasool
# ACR-SA: Attention-based deep model through two-channel CNN and Bi-RNN for sentiment analysis.
The convolutional neural networks (CNN) and recurrent neural networks (RNN) have been successfully applied to natural language processing (NLP), especially in sentiment analysis. The existing research shows that RNN achieved meaningful results than CNN due to extracting long-term dependencies. Meanwhile, CNN has its advantage; it can extract high-level features using its local fixed-size context at the input level. However, integrating these advantages into one network is challenging because of overfitting in training. Another problem with such models is the consideration of all the features equally. To this end, we propose an attention-based sentiment analysis to address the aforementioned problem and improve sentiment knowledge. Firstly, we apply intelligent preprocessing to enhance the data quality by correcting spelling mistakes and removing noisy content. Secondly, our model utilizes CNNs with max-pooling to extract contextual features and reduce features' dimensionality. Thirdly, two independent Bi-direction RNN, i.e., long short-term memory and gate recurrent unit (LSTM and GRU), are used to capture long-term dependencies. We also applied the attention mechanism at the RNNs layer output to emphasize each word's attention level. Furthermore, we utilized Gaussian noise and dropout as regularization to avoid the overfitting problem. We verify the model's robustness on four standard datasets. Compared with existing improvements on the most recent neural network models, the experiment results show that our model significantly outperformed the state-of-the-art models.

# Datasets.
IMDB: https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Sentiment140: http://help.sentiment140.com/for-students

US-airline : https://www.kaggle.com/crowdflower/twitter-airline-sentiment
