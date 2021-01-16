# Certificado de Machine Learning

### Composición del curso

El curso consta de dos partes claramente diferenciadas: una teórica y otra práctica.

- En la parte de teoría hay seis notebooks con códigos y texto dónde se explican algunos temas fundamentales dentro del mundo del Machine Learning. De esta forma, se introduce el framework TensorFlow para trabajar con código para aplicaciones de aprendizaje automático, se conocen los principales algoritmos fundamentales que existen en el mundo del *machine learning*, se explica también lo que son las redes neuronales y cómo trabajar con ellas, se aprende a desarrollar una red neuronal convolucional para aplicaciones de visión artificial, se explica y desarrolla una red neuronal recurrente para comprender el lenguaje humano y por último se explica lo que es el aprendizaje por refuerzo.

- En la parte de proyectos hay un total de 5 proyectos desarrollados en Python gracias al framework TensorFlow

The file `RPS.py` shows an example function that you will need to update. The example function is defined with two arguments (`player(prev_play, opponent_history = [])`). The function is never called with a second argument so that one is completely optional. The reason why the example function contains a second argument (`opponent_history = []`) is because that is the only way to save state between consecutive calls of the `player` function. You only need the `opponent_history` argument if you want to keep track of the opponent_history.

*Hint: To defeat all four opponents, your program may need to have multiple strategies that change depending on the plays of the opponent.*

### Development

Do not modify `RPS_game.py`. Write all your code in `RPS.py`. For development, you can use `main.py` to test your code. 

`main.py` imports the game function and bots from `RPS_game.py`.

To test your code, play a game with the `play` function. The `play` function takes four arguments:
- two players to play against each other (the players are actually functions)
- the number of games to play in the match
- an optional argument to see a log of each game. Set it to `True` to see these messages.

```py
play(player1, player2, num_games[, verbose])
```
For example, here is how you would call the function if you want `player` and `quincy` to play 1000 games against each other and you want to see the results of each game:
```py
play(player, quincy, 1000, verbose=True)
```

Click the "run" button and `main.py` will run.

### Testing 

The unit tests for this project are in `test_module.py`. We imported the tests from `test_module.py` to `main.py` for your convenience. If you uncomment the last line in `main.py`, the tests will run automatically whenever you hit the "run" button.

### Submitting

Copy your project's URL and submit it to freeCodeCamp.
