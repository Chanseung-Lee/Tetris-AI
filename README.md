# Tetris Game AI

A simple (but functional!) AI that can play the world-famous Tetris Game. It uses Numpy packages for machine learning operations, as well as PyQt5.

**tetris_game.py** is the main application for the game. **tetris_model.py** is the data model for the game, and **tetris_ai.py** handles the AI portion of the project!

If you wish to speed up & slow down the play speed, adjust the value of `Tetris.speed` defined here:
Higher value equals slower play speed!

```python
class Tetris(QMainWindow):
    ...
    def initUI(self):
        ...
        self.speed = 10
```
