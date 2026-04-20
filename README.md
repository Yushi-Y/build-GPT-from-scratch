# Neural-Networks-Zero-to-Hero

My take of the course "[Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)" by Andrej Karpathy.

1. [micrograd](https://github.com/Yushi-Y/Neural-Networks-Zero-to-Hero/blob/main/micrograd.ipynb): Step-by-step spelled-out explanation of backpropagation and training of neural networks.
2. [makemore-Part1-bigrams](https://github.com/Yushi-Y/Neural-Networks-Zero-to-Hero/blob/main/makemore_part1_bigrams.ipynb): Implement a simple network for bigram character-level language modeling.
3. [makemore-Part2-MLP](https://github.com/Yushi-Y/Neural-Networks-Zero-to-Hero/blob/main/makemore_part2_mlp.ipynb): Implement a multilayer perceptron (MLP) character-level language model.
4. [makemore-Part3-BatchNorm](https://github.com/Yushi-Y/Neural-Networks-Zero-to-Hero/blob/main/makemore_part3_bn.ipynb): Explore the internals of MLPs with multiple layers and examine the statistics of forward pass activations, backward pass gradients, and some pitfalls when they are scaled incorrectly. Introduce Batch Normalization.
5. [makemore-Part4-BackProp](https://github.com/Yushi-Y/Neural-Networks-Zero-to-Hero/blob/main/makemore_part4_backprop_ninja.ipynb): Take the 2-layer MLP (with BatchNorm) implemented previously and backpropagate through it MANUALLY without using PyTorch autograd's loss.backward(): through the cross entropy loss, 2nd linear layer, tanh, batchnorm, 1st linear layer, and the embedding table.
6. [makemore-Part5-WaveNet](https://github.com/Yushi-Y/Neural-Networks-Zero-to-Hero/blob/main/makemore_part5_cnn.ipynb): Take the 2-layer MLP implemented previously and make it deeper with a tree-like structure, arriving at a convolutional neural network architecture similar to the WaveNet (2016) from DeepMind.
7. [GPT-dev](https://github.com/Yushi-Y/Neural-Networks-Zero-to-Hero/blob/main/gpt_dev.ipynb): Build a character-level Generatively Pretrained Transformer (GPT) following the paper "Attention is All You Need".
   
Source code:
- [The micrograd Repo](https://github.com/karpathy/micrograd)
- [The makemore Repo](https://github.com/karpathy/makemore)
- [The nanoGPT Repo](https://github.com/karpathy/nanoGPT)
