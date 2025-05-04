# pide

This is an implementation of the algorithm in the paper 'An unsupervised deep learning approach to solving partial integro-differential equations' (https://www.tandfonline.com/doi/abs/10.1080/14697688.2022.2057870)

### Abstract:
We investigate solving partial integro-differential equations (PIDEs) using unsupervised deep learning. The PIDE is employed for option pricing, when the underlying process is a Lévy process with jumps. The unsupervised deep learning approach employs a neural network as the candidate solution and trains the neural network to satisfy the PIDE. By matching the PIDE and the boundary conditions, the neural network would yield an accurate solution to the PIDE. Unlike supervised learning, this approach doesn't require any labels for training. Additional singular terms are added to the neural network to satisfy the non-smooth initial conditions. Once trained, the neural network would be fast for calculating option prices as well as option Greeks.
