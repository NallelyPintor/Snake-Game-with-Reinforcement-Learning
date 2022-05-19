
# Development of the snake game with reinforcement learning in pytorch and pygame.

### Installation of Libraries:
- pip install pygame
- pip install torch torchvision
- pip install matplotlib ipython

### The project is divided into 4 parts:
1. Game: it is the normal snake game with a reset function, a reward function, a function that calculates the direction for each action, a game iteration function and a collision function
2. Agent: where we link the game, model and helper code
3. Model: Here the learning with the Pytorch library is developed
4. Helper: the graph of the scores against the number of games in training is obtained

#### Note:
There is a message board on PyData where some developers claim that jupyter does not support GUI . PyGame can only use the local video card and local monitor. Therefore, Jupyter Notebook or Colab can not run Pygame on its own, conditioning is needed to simulate the server's video card. It is recommended to use conda and manage the environments.
#### Sources
- https://github.com/python-engineer/snake-ai-pytorch
- https://stackoverflow.com/questions/57043905/how-can-we-use-pygame-on-google-colab
- https://stackoverflow.com/questions/69825188/can-not-import-pygame-in-jupyter-notebook-even-though-it-is-installed-correctly#comment123426072_69825188
