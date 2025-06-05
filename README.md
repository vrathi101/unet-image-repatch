trained autoencoder to fill in random white patch on input image

originally tried using denoising autoencoder but was unsuccessful, despite experimenting with various architectures, loss function(s), etc.

eventually switched over to unet architecture with skip connections; implemented custom architecture based on my interpretation of the paper: https://arxiv.org/pdf/1505.04597
was considering to use partial convolutional layers but decided it was overkill, more of proof-of-concept 
