# chessEngine
Building a chess convolutional neural network (CNN) to predict evaluation of a chess position.

Data taken from lichess which elo > 2000 and random board states.


## chessBoardGenerator.ipynb
Generates random moves of board to understand how to convert board states into matrix for the CNN to understand

## chessNeuralNetwork.ipynb
Reads games from lichess database and randomly generates board states for data. Converts each move of the game into a board state (14x8x8 matrix) and <br/>
evaluation by stockfish for label.

Training and testing the model by seeing how its evaluation on test data compares with stockfish
