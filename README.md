# PyTorch Practice
 
A few notebooks from me learning PyTorch — mostly working through the basics by implementing things from scratch instead of just using the built-in layers.
 
## What's in here
 
- **backprop_code.ipynb / backprop_code_1.ipynb** — implementing backpropagation manually to actually understand what `.backward()` is doing under the hood
- **simple_rnn.ipynb** — a basic RNN, built to get a feel for sequence models before jumping into anything fancier
- **CNN_pytorch.ipynb** — a CNN for image classification
## Running these
 
Just need PyTorch and Jupyter:
 
```bash
pip install torch torchvision jupyter
jupyter notebook
```
 
Nothing fancy — open whichever notebook and run it top to bottom.
 
## Why
 
Wanted to actually understand backprop and basic architectures instead of just calling `nn.RNN()` and `nn.Conv2d()` without knowing what's happening inside. Will probably add more as I go (LSTMs / attention next, maybe).
