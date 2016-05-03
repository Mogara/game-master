# game-master
Game Master is a set of tools to train artificial intelligence which can defeat human in playing games.

## Structure
Generally, there are three modules in Game Master.
- Preprocessor. Transform the data in other forms into listable form for later processing. For example, monitor the game UI and track the items in the game scene. Meanwhile, recongnize the speeds, directions and other states in the game and make the data structed.
- Processor. Make decisions. This module works just like a human's brain. It make decisions automatically due to the situation in the game. We provide generic decision models, machine learning and deep learning tools for training and model generation.
- Controller. Simulate human's inputs. For some games, simulate a touch or a click. For another, send keyboard signals. As we expected, it should support complicated gesture simulation.
