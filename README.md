# AI Flappy Bird 

This project is an **AI-powered Flappy Bird clone** built using Python, Pygame, and NEAT (NeuroEvolution of Augmenting Topologies). Instead of a human player, a neural network learns to play the game by evolving over generations through natural selection.

---

## What It Does

- Trains multiple birds to play Flappy Bird using NEAT.
- Birds improve over generations by evolving their neural networks.
- No pre-labeled data — the AI learns entirely through trial and error.
- Visualizes real-time training with game graphics and generation stats.

---

## Technologies Used

- **Python 3**
- **Pygame** – for game development and rendering
- **NEAT-Python** – for implementing neuroevolution

---

## How It Works

- Each bird (agent) is controlled by a neural network.
- The networks receive inputs like bird position, distance from pipes, and pipe height.
- Based on inputs, the network decides whether to flap or not.
- The fittest birds (those that survive longer or pass more pipes) pass on their genes.
- Over generations, the birds improve at playing the game autonomously.

---
