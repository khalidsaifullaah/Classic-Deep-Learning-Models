
<h1 align="center">
  <br>
  <a style ="color:black; text-decoration:none;" href="https://khalidsaifullaah.github.io/pathfinding-visualizer/">GAN (Generative Adversarial Network)</a>
</h1>

<h4 align="center">The model learns to generate images of digits using MNIST dataset</h4>


<p align="center">
  <a href="#live-demo">Live Demo</a> •
  <a href="#development-stack">Development Stack</a> •
  <a href="#brief-info-about-the-algorithms">Brief Info About The Algorithms</a> •
  <a href="#credits">Credits</a>
</p>

<div style="text-align:center"><img src="https://github.com/khalidsaifullaah/Classic-Deep-Learning-Models/blob/master/GAN/GAN_training.gif?raw=true"/></div>



## Framework
<h1 align="center">
<img width="80%" height="100" src="https://upload.wikimedia.org/wikipedia/commons/9/96/Pytorch_logo.png" alt="P5.js logo">
</h1>

## Brief Info About The Training Process

<p align="center">
<img width="20%" height="100" src="./untrained_image.png">
<p align="center">figure 1: generated image without any training</p>
</p>

<p align="center">
<img width="20%" height="100" src="./untrained_image.png">
<p align="center">figure 2: generated image at first epoch of training</p>
</p>

<p align="center">
<img width="20%" height="100" src="./untrained_image.png">
<p align="center">figure 1: generated image without any training</p>
</p>


>> At the very begining the **Generator** model is totally dumb, don't know how to make an image of a digit, thus generates totally noisy, random, fake images [figure 1]. **Discriminator** comes to rescue here, It's job is to discriminate real images of MNIST dataset from the fake images produced by the Generator. Discriminator easily identifies the fake images as they are really terrible at initial epochs [figure 2]. However as time passes, with the help and feedback of Discriminator, Generator starts to get the pattern and produces good fake images that successfully fools the Discriminator



- ### **Best-First Search (Greedy):**
    ![screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Dijkstra_Animation.gif/220px-Dijkstra_Animation.gif)
    
    Best-first search is a search algorithm which explores a graph by expanding the most promising node chosen according to a specified rule.
    Judea Pearl described best-first search as estimating the promise of node n by a "heuristic evaluation function {\displaystyle f(n)}f(n) which, in general, may depend on the description of n, the description of the goal, the information gathered by the search up to that point, and most important, on any extra knowledge about the problem domain."
    Some authors have used "best-first search" to refer specifically to a search with a heuristic that attempts to predict how close the end of a path is to a solution, so that paths which are judged to be closer to a solution are extended first. This specific type of search is called greedy best-first search or pure heuristic search.
    _-Wikipedia_

_*Note\: The GIF images are unashamedly taken from Wikipedia as well*_


## Credits


- [Daniel Shiffman's](https://github.com/shiffman/) video resources on P5.js helped me a lot to get a clear understanding about the library.
- [Clément Mihailescu's](https://github.com/clementmihailescu) similar project inspired me a lot for the UI and the project itself
- [P5.js](https://p5js.org/) The library behind the viz


## You may also like...

- [8-Puzzle Using A* Search](https://khalidsaifullaah.github.io/8-Puzzle-A-Star-Search/) - Interactive way to solve the puzzle or get it solved by the AI


---

> Stack Overflow [@khalid-saifullah](https://github.com/khalidsaifullaah) &nbsp;&middot;&nbsp;
> GitHub [@khalidsaifullaah](https://github.com/khalidsaifullaah) &nbsp;&middot;&nbsp;
> Facebook [@ikhalidsaifullaah](https://www.facebook.com/ikhalidsaifullaah/) &nbsp;&middot;&nbsp;
> Twitter [@k_saifullaah](https://twitter.com/k_saifullaah) &nbsp;&middot;&nbsp;
> LinkedIn [@khalidsaifullaah](https://www.linkedin.com/in/khalidsaifullaah/)

