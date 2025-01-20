# Overview
GPTForge is a PyTorch-based implementation of a language model inspired by Andrej Karpathy's "makemore" YouTube series. This project demonstrates the creation of a transformer-based language model from scratch, showcasing key concepts in natural language processing and deep learning. The transformer model is a generative AI, it generates text similar to the training data(Shakespeare's entire  literature work).

##  Getting Started

###  Prerequisites
-  Python 3.7+
-  pip(Python package installer)
-  CUDA 10.1 or higher (for GPU support)

###  Clone the Repository
```bash
git clone https://github.com/yourusername/GPTForge.git
```

###  Install the required packages

```bash
pip install -r requirements.txt
```

###  Training the model

1. Launch the Jupyter notebook
```bash
jupyter notebook
```
2.  Load your text data into the input.txt file.
   
3.  Run the model notebook to start training and text generation


##  Project Structure

The project consists of several key components:
1.  Data Preparation: Loads and processes text data for model training.
2.  Model Architecture: Defines the transformer-based language model.
3.  Training: Implements the training loop and loss calculation.
4.  Text Generation: Provides functionality to generate new text using the trained model.

##  Model Architecture
The model includes:
-  Token and positional embeddings
-  Multi-head self-attention layers
-  Feedforward neural networks
-  Layer normalization

##  Training
The model is trained using:
-  AdamW optimizer
-  Cross-entropy loss
-  Gradient clipping for stability

##  Acknowledgements
This project is based on the concepts and techniques taught by Andrej Karpathy in his "makemore" YouTube series. It serves as an educational implementation of transformer-based language models.
