# Autoencoder and Variational Autoecoder(VAE)

### What is an Autoencoder?

Autoencoders (AE) are neural networks that aim to copy their inputs to their outputs. They work by compressing the input into a latent-space representation and then reconstructing the output from this representation.


An autoencoder consists of two primary components:


**Encoder**: Learns to compress (reduce) the input data into an encoded representation.

**Decoder**: Learns to reconstruct the original data from the encoded representation to be as close to the original input as possible.

**Bottleneck/Latent space**: The layer that contains the compressed representation of the input data.

**Reconstruction loss**: The method measures how well the decoder is performing, i.e. measures the difference between the encoded and decoded vectors. Lesser the better.
