# AlphaZero
Implementation of the [AlphaZero](https://arxiv.org/pdf/1712.01815v1.pdf) algorithm.  
 
## Introduction
This repo contains: 
- an implementation of the AlphaZero algorithm 
- an agent that uses the alphazero to play a zero sum game (TicTacToe)

### Project details

The code has been adapted from [Udacity Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893 "Udacity Deep Reinforcement Learning Nanodegree").

This is an implementation of a an agent that uses an implementation of the AlphaZero algorithm in order to play the board game of TicTacToe.

### Getting Started

Follow the instructions into the notebook in order to play against the agent! 

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name alphazero python=3.6
	source activate alphazero
	```
	- __Windows__: 
	```bash
	conda create --name alphazero python=3.6 
	activate alphazero
	```

3. Clone the repository, and then, install the required packages (see requirements).
```bash
git clone https://github.com/ciamic/alphazero.git
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `alphazero` environment.  
```bash
python -m ipykernel install --user --name alphazero --display-name "alphazero"
```

5. Before running code in a notebook, change the kernel to match the `alphazero` environment by using the drop-down contextual `Kernel` menu. 

### Requirements

- `Python 3`
- `numpy`
- `matplotlib`
- `Torch`
