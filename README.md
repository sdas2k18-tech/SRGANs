# SRGANs
Super resolution using GANs.

Techstack- Python, tensorflow, Generative Adversal natworks, keras, CNN, Image Classification, Image Upscaling, Matplotlib, Deep Learning, Machine Learning etc.

Super-Resolution Generative Adversarial Network, or SRGAN, is a Generative Adversarial Network (GAN) that can generate super-resolution images from low-resolution images, with finer details and higher quality. CNNs were earlier used to produce high-resolution images that train quicker and achieve high-level accuracy. However, in some cases, they are incapable of recovering finer details and often generate blurry images. 

GANs is a Deep Learning architecture that uses two neural networks to compete against each other to generate new data from a training dataset. The two Neurak Networks Models are called **the generator and the discriminator**.

The generator learns to create plausible data, while the discriminator learns to distinguish the generator's fake data from real data. 

In SRGANs, Generator Network will produce high resolution images from low resolution images using CNN. The generated images will be compared to a real high resolution image image in discriminator distinguish as real or fake. That would in return would train the generator Netork to produce more realistic image. So with easch iteration the quality of image gets better and eventually produces no blurry, finer, high quality realistic super reolution resolution images.

