# BasicDCGAN
 A basic DCGAN project using fashion mnist dataset
 
This is a DCGAN model with a CNN architecture consisting of only few layers of convolutions.
The famous fashionMNIST dataset has been used to train the model.<br> Generative Adversarial 
Networks or GANs are a generative modeling approach using Deep Learning to train the model in a 
clever manner to generate data by using the sub-model approach. <br>

Deep Convolutional Generative Adversial Networks (DCGANs in short) are the GANs which use the
**Convolution** technique. <br>

These models contain two sub-models. <br>
- **G -> Generator** is an upsampling network with fractionally-strided convolutions.

- **D -> Discriminator** is a convolutional network too.

One of the most interesting parts of Generative Adversarial Networks is the design 
of the Generator network. The Generator network is able to take random noise and map it 
into images such that the discriminator cannot tell which images came from the dataset 
and which images came from the generator (The most famous analogy '**Two player game**'). 
**D** is trained such that it classifies the images coming from the dataset distribution from
those coming from other distributions (fake images). **G** is trained so that it can fool **D**.
So, mathematically speaking, **G** tries to increase the probability that **D** mis-classifies 
a fake-image(generated image) as coming from the dataset distribution.

All the ideas in the [notebook](https://github.com/ManojBoganadham/BasicDCGAN/blob/master/DCGAN.ipynb)
are from the original research paper (due to  Radford er al, 
"*Unsupervised Representation Learning with Deep Convolutional Generative Adversial Networks*",
 ICLR 2016GANs ) of DCGANs [here](https://arxiv.org/pdf/1511.06434.pdf) 

You can learn more about DCGANs from the guided project [Generate Synthetic Images with DCGANs in Keras](
https://www.coursera.org/projects/generative-adversarial-networks-keras)

By **[Manoj Boganadham](https://github.com/ManojBoganadham)**


 
