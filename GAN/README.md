
<h1 align="center">
  <br>
  <a style ="color:black; text-decoration:none;" href="https://khalidsaifullaah.github.io/pathfinding-visualizer/">GAN (Generative Adversarial Network)</a>
</h1>

<h4 align="center">The model learns to generate images of digits using MNIST dataset</h4>


<p align="center">
  <a href="#live-demo">Live Demo</a> •
  <a href="#development-stack">Development Stack</a> •
  <a href="#brief-info-about-the-algorithms">Brief Info About The Training Process</a> •
<a href="#framework">Framework</a> •
  <a href="#plots">Plots</a>
</p>

<h1 align="center"><img src="https://github.com/khalidsaifullaah/Classic-Deep-Learning-Models/blob/master/GAN/GAN_training.gif?raw=true"/></h1>



## Brief Info About The Training Process

<p align="center">
<img src="./untrained_image.png">
<p align="center">figure 1: generated image without any training</p>
</p>

<p align="center">
<img src="./first_epoch_fake_image.png">
<p align="center">figure 2: generated image at first epoch of training</p>
</p>

<p align="center">
<img src="./fake_images-0500.png">
<p align="center">figure 3: generated image at 50th epoch of training</p>
</p>


>> At the very begining the **Generator** model is totally dumb, don't know how to make an image of a digit, thus generates totally noisy, random, fake images [figure 1]. **Discriminator** comes to rescue here, It's job is to discriminate real images of MNIST dataset from the fake images produced by the Generator. Discriminator easily identifies the fake images as they are really terrible at initial epochs [figure 2]. However as time passes, with the help and feedback of Discriminator, Generator starts to get the pattern and produces good fake images that successfully fools the Discriminator



## Framework

<img width="50%" height="50%" src="https://upload.wikimedia.org/wikipedia/commons/9/96/Pytorch_logo.png" alt="P5.js logo">



## Plots
<p align="center">
<img width="50%" src="./lossVepoch.png">
<img width="50%" src="./accuracyVepoch.png">
</p>



---

> Stack Overflow [@khalid-saifullah](https://github.com/khalidsaifullaah) &nbsp;&middot;&nbsp;
> GitHub [@khalidsaifullaah](https://github.com/khalidsaifullaah) &nbsp;&middot;&nbsp;
> Facebook [@ikhalidsaifullaah](https://www.facebook.com/ikhalidsaifullaah/) &nbsp;&middot;&nbsp;
> Twitter [@k_saifullaah](https://twitter.com/k_saifullaah) &nbsp;&middot;&nbsp;
> LinkedIn [@khalidsaifullaah](https://www.linkedin.com/in/khalidsaifullaah/)

