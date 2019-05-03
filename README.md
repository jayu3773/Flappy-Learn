# Flappy-Learn
## Neuroevolution of Flappy Bird game

[Play here](https://sahil-tah.github.io/Flappy-Learn/)

<p align="center">
  <img src="assets/game.png" height="350">
</p>

<p align="center">
  <sub>Created by <a href="https://github.com/Sahil-Tah"><strong>Sahil Tah</strong></a>
</p>
<hr noshade>

### Libraries

* **P5.js**
* **Particle.js**

### Explanation
This Project uses neural-network & genetic algorithm for bird's brain. Input of the neural network consists of Bird's y-position, closest distance to the pipe x-distance, upper pipe's y-dist and bottom pipe's y-distance. The output will be probabilty score of between 0 and 1, if greater than 0.5 jump else don't jump.

![nn](assets/nn.png)

### References
* **The Coding Train** [NN](https://github.com/CodingTrain/Toy-Neural-Network-JS)
* **Demystifying Reinforcement Learning** [Intel](https://www.intel.ai/demystifying-deep-reinforcement-learning/#gs.0lgpgr)
