#### Shakespearean Text Generation with LSTM

This project demonstrates text generation using LSTM (Long Short-Term Memory) networks trained on Shakespearean text. Given a seed text, the model generates new text that resembles Shakespeare's writing style.
Overview

Text generation is a natural language processing task where a model learns the patterns and structure of a given text corpus and generates new text based on that learning. In this project, we use LSTM neural networks, a type of recurrent neural network (RNN), to generate Shakespearean text.
Project Structure

    train_model.ipynb: Jupyter Notebook containing code for training the LSTM model on the Shakespearean text data.
    generate_text.ipynb: Jupyter Notebook containing code for generating text using the trained model.
    shakespeare.txt: Text file containing the collected works of William Shakespeare.
    model_weights.h5: Trained weights of the LSTM model.
    tokenizer.pickle: Pickle file containing the tokenizer used for text tokenization.
    README.md: This README file providing an overview of the project.

Dependencies

    Python
    TensorFlow
    Keras
    NumPy
