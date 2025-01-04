# Text-Generation-using-Python

## Overview
This project implements a text generation model using PyTorch. It uses a Conv1D layer for local feature extraction, LSTM layers for sequential understanding, and dense layers for prediction.

## Steps to Run
1. Install dependencies: pip install torch, torchvision, spacy | -m spacy download en_core_web_sm
2. Place the text file (`Kate bonnet.txt`) in the project directory.
3. Run the preprocessing script from the TextGeneration.ipynb
4. Train the model.
5. Generate text.

## Sample Output
Seed Text: "I was playing in the garden and ball"
Generated Text: "It was a dark and stormy night the rain fell heavily and thunder roared through the darkness."
