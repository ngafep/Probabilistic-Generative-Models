# Probabilistic Generative Models

In this notebook project, generative models, specifically normalizing flow networks and the variational autoencoder algorithm, will be used. A synthetic dataset will be created with a normalizing flow using randomized parameters. This dataset will then be used to train a variational autoencoder, and the trained model will be used to interpolate between the generated images. Concepts such as Distribution objects, probabilistic layers, bijectors, ELBO optimization, and KL divergence regularizers will be utilized.

For this project, an image dataset will be created from contour plots of a transformed distribution using a random normalizing flow network. The variational autoencoder algorithm will then be used to train generative and inference networks, and new images will be synthesized by interpolating in the latent space.
