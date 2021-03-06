# AutoEncoders
Beside generating a reduced representation of images or any non-linear data. AutoEncoders can also be used to generate the images back from the reduced representation. This also makes them a type of generative model. This repository shall have implementations of the different types of AutoEncoders.

1. Vannila Autoencoder: The most simple autoencoder. Where the images go through an encoder model and then the decoder model to generate back the image. This implementation uses only Dense layers and hence is the most basic implementation and extracts 2 latent features. The Encoder, Decoder and the complete AutoEncoder model have been implemented. 

2. Convolution Autoencoder: A simple autoencoder implemented using CNN. The images go through an encoder model and then the decoder model to generate back the image. This generates better images than Vanilla Autoencoder because we have extracted 10 latent features and also used CNN along with Dense layers.

3. Denoising Autoencoder: Sometimes the autoencoder may learn to memorise that it learns an identity function that maps the input to the output. Therefore to prevent this we add some noise to the input and train the model. But the loss function calculates loss between output and the original images. This prevents the encoder-decoder model from memorising.
