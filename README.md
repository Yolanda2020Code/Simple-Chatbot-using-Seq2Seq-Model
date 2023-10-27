# Simple Chatbot using Seq2Seq Model

This project presents a rudimentary chatbot built using Seq2Seq models leveraging the Encoder-Decoder architecture.

## Description:
- The Encoder processes the input sequence and compresses the information into a context vector.
- The Decoder takes this context vector to produce the output sequence.
- LSTM layers are used for both the Encoder and the Decoder.

## Requirements:
- tensorflow>=2.0
- keras>=2.4.0
- numpy>=1.18.0

## Usage:
1. Modify the `input_texts` and `target_texts` lists with your conversation data.
2. Ensure required libraries are installed.
3. Run the code to train the chatbot model on your dataset.
4. With further enhancements, the model can be used to predict responses for user queries.

**Note**: This is a basic demonstration. For a practical chatbot, consider more complex architectures, attention mechanisms, and a comprehensive dataset.
