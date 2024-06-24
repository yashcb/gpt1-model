# Welcome to the Large Language Model Project based on the GPT architecture!

## Overview : 

This project aims to implement a large language model from scratch, inspired by the architecture of OpenAI's GPT (Generative Pre-trained Transformer). The goal is to develop a model capable of generating human-like text based on the patterns and structures it learns from a vast amount of textual data.

The project is inspired from amazing [**Elliot Arledge**](https://github.com/Infatoshi)'s **Intro to LLMs** 

## Features:

- **Transformer Architecture:** Utilizes the transformer model for handling sequential data and capturing long-range dependencies.
  
- **Self-Attention Mechanism:** Implements self-attention layers to weigh the significance of different words in context.
  
- **Multi-Head Attention:** Enhances the model's ability to focus on different parts of the input sequence simultaneously.
  
- **Feedforward Neural Networks:** Includes feedforward layers to process information after attention mechanisms.
  
- **Positional Encoding:** Incorporates positional encodings to provide information about the position of tokens in the sequence.


## Getting Started:

To get started with the project, follow these steps:

1. Clone the Repository: Clone this repository to your local machine with

   `git clone https://github.com/yashcb/gpt1-model.git`

3. Install Dependencies: Ensure all necessary dependencies are installed. Assuming Windows

   `pip install pylzma numpy ipykernel jupyter torch --index-url https://download.pytorch.org/whl/cu118`

5. Prepare Data: Obtain any large corpus of text data for training the language model, I've used `https://skylion007.github.io/OpenWebTextCorpus/`. Preprocess the data and create ***train-val*** splits with `data-extract.py`

6. Train the Model: Train the language model. Adjust hyperparameters and experiment with different configurations as needed.

7. Evaluate and Generate: Evaluate the model's performance on language modeling tasks. Generate text samples to observe the quality of generated outputs.

## Contributing
Contributions are welcome! If you'd like to improve the model architecture, add features, or fix bugs, please feel free to fork the repository and submit a pull request.

## Socials
_LinkedIn_ : https://www.linkedin.com/in/y304/
