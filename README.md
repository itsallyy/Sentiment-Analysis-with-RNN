# Sentiment-Analysis-with-RNN
This project implements a **deep learning model for sentiment analysis** on the **IMDB Dataset of 50K Movie Reviews**. You can email me for getting access to the dataset.

After extensive preprocessing— including removing HTML tags, cleaning non-alphabetic characters, tokenization, and applying the **Porter Stemming** algorithm— a vocabulary of 5,000 tokens was created.

Two common architectures, **LSTM** and **GRU**, were tested with various configurations of embedding dimensions (50 and 100) and hidden states (128 and 256). Different dropout rates (0.2, 0.3, 0.5) were compared in a simple grid search. The best configuration was achieved using a **GRU network** with a hidden size of 100, embedding dimension of 100, and dropout rate of 0.3.

The final model reached **90% test accuracy**, along with high **precision, recall, and F1-score (0.90)**. A **confusion matrix** was also used to analyze misclassifications. The report concludes with detailed parameter tuning results and final performance analysis.
