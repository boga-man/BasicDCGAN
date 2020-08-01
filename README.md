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

<img src='https://www.bing.com/images/search?view=detailV2&ccid=s8nnfyFk&id=23ED777F99ACB93DADC80A7B7FC39E6ABEDB3D3A&thid=OIP.s8nnfyFk45gDWp9kox-HxwHaCq&mediaurl=https%3a%2f%2fwww.researchgate.net%2fpublication%2f331282441%2ffigure%2fdownload%2ffig3%2fAS%3a729118295478273%401550846756282%2fDeep-convolutional-generative-adversarial-networks-DCGAN-for-generative-model-of-BF-NSP.png&exph=305&expw=850&q=dcgan&simid=608001166798751611&ck=7DDD68D193DB873698266BE4653A6EEE&selectedindex=5&form=IRPRST&ajaxhist=0&first=1&scenario=ImageBasicHover'>
<br>
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


 
