# The Goal

The aim of this project was to learn more about the creation and implementation of machine learning in language models. Frameworks used were Pytorch as well as the TikToken library from OpenAI. I followed Andrej Karpathy's online lectures to learn more about the implementation of the transformer architecture and made my own changes to make the model perform better on Latex, since a wider context window was required for proper formatting.

I also implemented dropout and learning rate decay for better eval performance. Ended up with some somewhat readable latex code, but more importantly gained many valuable skills in pytorch and NN training.

Bigram.ipynb --- Basic bigram model (test TikToken set up conda on MPS)

Trigram.ipynb --- trigram model with transformer architecture

