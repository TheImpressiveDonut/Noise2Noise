# Noise2Noise and Autoencoders

The goal of the first project is to implement an image
denoising network trained without a clean reference image
following the Noise2Noise (N2N) paper [1]. The data given
comprises a training dataset containing 50000 pair of noisy
images of size 32x32 and validation dataset of 1000 images
of size 32x32 to verify our performance. The dataset is pretty
diverse and pair of images represent of a different scene(e.g.
a dog, an insect, ...). This report presents how we handled the
task, by presenting our model, which modifications and the
data augmentation techniques we used. \
The data is available at https://drive.google.com/drive/u/2/folders/1CYsJ5gJkZWZAXJ1oQgUpGX7q5PxYEuNs (use an google account)
