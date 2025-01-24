This project involves training an AI to play Flappy Bird using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm.
The AI learns how to play the game by evolving neural networks that control the bird's movements.

python -m venv venv
source venv/bin/activate (Linux, macOS) or venv\Scripts\activate (Windows)
pip install -r requirements.txt

config-feedforward.txt - configures NEAT parameters like population size, mutation rates, and neural network inputs/outputs.
python train-net.py - train your AI flappy bird
python test-net.py - test your net

bias/weight init reduced from 1.0 to 0.5 to retard the process of learning
