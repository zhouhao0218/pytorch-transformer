# pytorch-transformer
Attention is all you need implementation

YouTube video with full step-by-step implementation: https://www.youtube.com/watch?v=ISNdQcPhsts

model.py - implementation of the transformer model

Dataset: hugging face https://huggingface.co/datasets/opus_books/viewer/en-es

train.py: Tokenizer - What comes before the input embeddings, goal: to create token, split sentence into single words (world level tokenizer) 

dataset.py: create tensor that model will use

config.py: model is too big for gpu to train, reduce the number of heads or the number of layers

attention_visual.ipynb: 