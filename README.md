# All-Convnet-TensorFlow-MNIST-Tutorial
A look at using conv nets all the way through for TensorFlows MNIST Tutorial

# Why All-Convnet
Recently I read the paper Striving for Simplicity: The All Convolutional Net [a link](http://arxiv.org/pdf/1412.6806.pdf). It seems based on this and similar papers I have looked at that Neural Networks might be heading to the all Conv architecture (for some image stuff). I wanted to play around with them a bit so I re-wrote the TensorFlow MNIST tutorial with the same general design as seen in the above paper. I thought it would be funny if this new approach, which is arguably much simpler, would compare to the standard MNIST tutorial.

# How to run
I included the `mnist.py` and `input_data.py` file just so there was no need to move anything around to get it to work. Just `python all_conv_mnist.py`

# Results
Sadly I was unable to reach 99.3 is accuracy that the normal tutorial gets. I was able to get around 97.5. I feel that structuring the layers as 3x3 and adding a few would probably get there (other people have of course done this) but to me that would make it more complicated then the normal MNIST Tutorial and thus kinda pointless.


