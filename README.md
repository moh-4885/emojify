# Emojify: Text-to-Emoji Model 🌐😊
This project is a machine learning model designed to convert text into emojis, adding a fun and expressive layer to text communication. Using pre-trained GloVe embeddings and an LSTM-based neural network, this project classifies text into its most suitable emoji representation.
## Data
This project uses pre-trained GloVe embeddings and a labeled dataset for text-to-emoji mapping. The GloVe embeddings are used to convert words into numerical vectors, allowing the model to interpret textual data.
<a href ="https://drive.google.com/drive/folders/151r0LvvSqb5dws97GWFrHAssWrScLeMQ?usp=sharing">Dataset link </a>
## Model
The model uses an LSTM layer to capture sequential patterns in text. It then classifies text into various emoji categories using a dense layer with softmax activation.

## Key components:

- Embedding Layer: Converts text into dense word vectors.
- LSTM Layer: Processes sequential patterns in the text.
- Dense Layer: Produces emoji classification output.
