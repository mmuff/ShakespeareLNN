# Shakespeare Sonnet Generator 

## Description 

This model is based on the LSTM (Long Short-Term Memory) architecture and was trained on a dataset of William Shakespeare's sonnets. The purpose of the model is to generate new text fragments in the style of Shakespeare, starting with a given starting word. The model predicts the next word in the text based on the previous words, taking into account the context and structure of the sonnets.

The model was trained on data from Project Gutenberg, which contains all 154 of William Shakespeare's sonnets.

## Features:
- Text Generation: The model takes a starting word as input and generates a sequence of words based on that word.
- Temperature: The model supports a "temperature" option, which modifies the randomness of the generated words. A lower temperature makes the model more deterministic, while a higher temperature increases the variety of the generated text.

## Requirements
To run this project, you need to have the following libraries installed:
- torch (PyTorch)
- requests
- numpy
- gradio (optional, if you want to run the Gradio interface)
