The respository is about: 

Implement a variational auto-encoder (VAE) and a generative adversarial network (GAN) in PyTorch to generate images similar to those in the MNIST dataset. 

As a starting point, a deterministic auto-encoder (DAE) achieves good reconstruction of the original images, they struggle to generate new images that are similar to those in MNIST. 

so, here implement a VAE and GAN to generate better images. 

Part 1: vae_skeleton.ipynb
Part 2: gan_skeleton.ipynb

Part 1:

VAE implementation in cs480_fall20_asst6_vae_skeleton.ipynb. 
Two graphs that each contain 2 curves (DAE and VAE). The first graph displays the training reconstruction loss and the second graph displays the testing reconstruction loss. In both graphs, the y-axis is binary cross entropy and the x-axis is the number of epochs.
Print a sample of generated images after each epoch of training for both DAEs and VAEs.
Explanation of the results (i.e., compare and explain the binary cross entropy and the quality of the sampled images generated by DAEs and VAEs).


Part 2:

GAN implementation in cs480_fall20_asst6_gan_skeleton.ipynb. 
Two graphs that each contain 2 curves (Generator and Discriminator losses). The first graph displays the training loss and the second graph displays the testing loss. In both graphs, the y-axis is binary cross entropy and the x-axis is the number of epochs.
Print a sample of generated images after each epoch of training for GAN.
Explanation of the results (i.e., compare and explain the quality of the sampled images generated by VAEs and GANs).
