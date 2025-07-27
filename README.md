# sentiment-analysis-imdb-dataset

This project performs sentiment analysis on the IMDb movie reviews dataset using pre-trained transformer models (BERT and RoBERTa) combined with six different neural network architectures:

    FNN (Feedforward Neural Network)
    RNN
    GRU
    LSTM
    BiLSTM
    TextCNN
It aims to classify reviews as positive or negative, and is especially useful for beginners interested in combining deep learning and transformer-based NLP models.


Dataset

    The dataset used is a preprocessed version of the IMDb dataset (dataset.csv), containing labeled reviews.
    Detailed preprocessing steps are available in this blog post.

Model Architecture

    The architecture fuses BERT/RoBERTa embeddings with deep learning models like GRU, LSTM, and CNN.
    Each configuration is run separately to compare performance.

Results

    Due to large dataset size, only 10% of the data was used for training.
    Results for various model combinations are visualized here:

<img width="1623" height="549" alt="image" src="https://github.com/user-attachments/assets/2fea0bce-22e6-47e7-85f1-6efec3083c8f" />

