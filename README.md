# Text Generation with minGPT

This repository contains code to train and use a text generation model based on the minGPT framework by Andrej Kaparthy. You can use the provided Jupyter Notebooks to train a model on your own selected data source and then generate text using the trained model.

## Files

### 1. `train_model.ipynb`

In this notebook, you can train your own GPT model based on the data source you choose. This is where you can customize the model architecture, training parameters, and more.

### 2. `use_model.ipynb`

This Jupyter Notebook demonstrates how to use a trained model to generate text. You can input your own prompts or let the model generate text from scratch.

### 3. `out/`

This directory contains the trained model weights saved after training. You'll find the checkpoints here, which you can use for inference or continue training.

### 4. `data_source/`

Place all your data sources in this directory. These can be text files, CSVs, or any format that contains the text you want your model to learn from.

## References

### minGPT by Andrej Kaparthy
[minGPT Github Repository](https://github.com/karpathy/minGPT)
