# Flappy Bird AI using NEAT

**Recreating the classic Flappy Bird game with artificial intelligence (AI) powered by NEAT (NeuroEvolution of Augmenting Topologies).**

## Overview

This project is an implementation of the popular Flappy Bird game where you control a bird to avoid obstacles and achieve a high score. In this version, the bird is controlled by AI using the NEAT algorithm, making it learn and eventually become invincible at the game.

## Requirements

Before running the game, make sure you have the following dependencies installed:

- Python (>= 3.6)
- pygame
- neat-python

You can install the required packages using pip:

```bash
pip install pygame neat-python
```
## How to Run
To run the Flappy Bird game with AI, follow these steps:

- Clone or download this repository to your local machine.
- Navigate to the project directory in your terminal.
- Run the game by executing the following command:

```bash
  python flappy_bird.py
```
The game will start, and you can watch the AI-controlled bird learn and play.

## Game Controls
If you're playing manually, press the SPACE key to make the bird jump.

## Game Features
- The game features a neural network powered by NEAT to control the bird's actions.
- The bird learns to navigate through obstacles and improve its score over time.
- The game keeps track of the current generation and displays it on the screen when AI is playing.

## Customizing the NEAT Configuration
You can fine-tune the NEAT algorithm by modifying the configuration file config.txt. This file includes various parameters that affect how the AI learns and evolves.

## Credits
This project was created by Tech With Tim as a demonstration of implementing NEAT in a popular game. The game assets are derived from the original Flappy Bird game. This is a recreation with learning purpuses. 

This is what the console output looks like
<div>
  <img align="center" alt="project demonstration gif" width="600" src="https://github.com/larissaborsari/flappy_bird_project/assets/81311347/36743892-a14f-4d1e-ae8a-6816c05fd25d">
</div>
<br>
<div>
 <img align="center" alt="project demonstration gif" width="600" src="https://github.com/larissaborsari/flappy_bird_project/assets/81311347/57189cf8-09a0-447b-9e45-c1ef6c0a4527">
</div>
