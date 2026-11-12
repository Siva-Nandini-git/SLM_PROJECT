# Small Language Model (SLM) Training

## Project Overview
This project focuses on building and training a Small Language Model (SLM) using Python and PyTorch with a custom dataset.

The model is trained to learn text patterns and generate text based on user prompts.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- PyTorch
- Matplotlib
- Hugging Face Tokenizers

## Dataset
The project uses a custom dataset containing 999 records.

| Dataset | Number of Records |
|---------|-------------------|
| Training | 799 |
| Testing | 100 |
| Validation | 100 |

## Model Details
- Model type: Small Transformer Language Model
- Parameters: 754,513
- Vocabulary size: 1,873
- Sequence length: 64
- Training epochs: 10
- Hardware acceleration: Apple Silicon MPS

## Project Files
- TRAIN.csv – Training dataset
- TEST.csv – Testing dataset
- VALIDATE.csv – Validation dataset
- slm_model.pth – Trained model weights
- slm_tokenizer.json – Custom tokenizer
- slm_training_data.csv – Processed training data
- slm_training_history.csv – Training and validation loss
- slm_training_graph.png – Training performance graph

## Results
The model was trained for 10 epochs. Training loss decreased from 5.8099 to 0.9292, while validation loss decreased from 4.2397 to 1.1591.

## Conclusion
This project demonstrates the development and training of a small language model using a custom dataset, tokenizer and Transformer architecture.

