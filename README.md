# Transformer-Based Text Summarizer

This repository implements a Transformer-based text summarization model using TensorFlow. The model processes input text and generates concise summaries using an encoder-decoder architecture with self-attention mechanisms.

## Features

- **Text Preprocessing**: Tokenizes input, builds vocabulary, and applies padding.
- **Transformer Model**: Implements an encoder-decoder architecture with multi-head attention.
- **Training Optimization**: Uses masked loss function and custom training steps.
- **Summarization Output**: Generates concise summaries from input text.

## Files

1. **`Transformer_Summarizer.ipynb`**: Python script implementing the summarization model.
2. **Dataset**: Text data for training and evaluation.
3. **Utility Functions**: Preprocessing and tokenization functions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulrahmanAhmed20072/Transformer-Text-Summarizer.git
   ```
2. Install the required Python packages:
   ```bash
   pip install tensorflow numpy pandas matplotlib
   ```

## Usage

1. Preprocess the dataset for tokenization and vectorization.
2. Train the Transformer model using the provided script.
3. Use the trained model to generate text summaries.

Run the script:
```bash
python Transformer_Summarizer.ipynb
```

## Outputs

- Trained Transformer model for text summarization.
- Predicted summaries for input documents.
- Loss progression during training.

## Example

Input Text:
```
Machine learning enables systems to learn and improve from experience.
```

Generated Summary:
```
ML helps systems improve over time.
```
