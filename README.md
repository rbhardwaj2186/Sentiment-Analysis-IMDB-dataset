# Sentiment Analysis IMDB dataset

## Sentiment Analysis with Different Neural Network Architectures
This project focuses on sentiment analysis using the IMDB movie reviews dataset. The goal is to classify movie reviews as either positive or negative based on the text content of the reviews.

The project explores different neural network architectures for the task, including:

Flatten Model: This model uses an embedding layer for word embeddings, followed by a flatten layer and two dense layers.

![Screenshot (3188)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/cb9532df-e8a2-4a59-80df-5ffb53e9489d)
![Screenshot (3189)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/30532ed7-534e-47e9-a4bc-bd1c3ccba443)

LSTM Model: This model uses an embedding layer followed by a bidirectional LSTM layer and two dense layers.

![Screenshot (3190)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/4a41d7c9-0bac-491f-b53d-ea954c0c6d8d)
![Screenshot (3191)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/8b6a61cf-7220-4ddd-80ac-ea14f32fa17a)

GRU Model: This model uses an embedding layer followed by a bidirectional GRU layer and two dense layers.

![Screenshot (3192)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/2cf7a36e-e688-4944-9313-6ee5b7f21c37)
![Screenshot (3193)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/4d5c6d1a-9449-458a-a30d-3c5d822d486a)



Convolution Model: This model uses an embedding layer followed by a Conv1D layer, a global average pooling layer, and two dense layers.

![Screenshot (3194)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/e172f716-0e17-400b-be33-78ac85a459e3)
![Screenshot (3195)](https://github.com/rbhardwaj2186/Sentiment-Analysis-IMDB-dataset/assets/143745073/bfed4268-51d1-4456-8585-f0b70cad97ba)



Each model is trained and evaluated on the IMDB movie reviews dataset. The training process includes tokenizing the reviews, padding the sequences to ensure uniform length, and encoding the labels. The performance of each model is visualized using accuracy and loss plots.

This project provides a comprehensive comparison of different neural network architectures for sentiment analysis on movie reviews. It serves as a valuable resource for understanding how different neural network architectures perform on a text classification task.
