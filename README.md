# VAEs

This aims to reconstruct a video sequance images through Variational autoencoder models(VAEs) and investigate the instric meaning of latent variables. Based on the realization of the first two objectives, the trajectory of object motion can be presented in low-dimensional latent space. In this process, the frames of moving objects are simulated through the image transform. Through the combination of the primary motion of multiple objects, we could develop a high-level understanding of moving trajectory and latent space.
---
## Environment Setting.

1. create an environment with Python 3.8
2. Activate the environment and the install the libraries in the requirements.txt file
   'pip install -r requirements.txt'
3. Finally, start Jupyter please.
---
## Objetive Setting.
1. Whether Variational Aucoder Models(VAEs) can reconstruct the sequence of images draw from a video? (It implies whether there is a meaningful latent space. )
2. What the intrinsic implications of each latent variable?(what aspect each latent variable controls?)
3. How an object moves in latent space?(What is the trajectory of the targets, which would be helpful for image reconstruction？)
---
## Folders introduction

### Fuctions 
It contains the image transofrmation function such as rotation and shift. And the codes are commented. Please go for more details in that Folder.
### Meaningful Examples 
They are well-behaved examples trained by The Variational Aucoder Model. Each example contains the whole experiments.
### Remaining Examples 
They are bad-behaved examples trained by The Variational Aucoder Model. Each example contains the part of experiments. In other words, it needs to do more works in the future.


