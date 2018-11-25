# MENACE_in_python
Python simulation of Machine Educable Noughts And Crosses Engine

### Inspiration

Here is what you need to know (where I learned about) MENACE: [https://www.youtube.com/watch?v=R9c-_neaxeU](https://www.youtube.com/watch?v=R9c-_neaxeU)
I saw this and thought to myself, I can code this.

### What?

Basically MENACE was designed in the 60s, to demonstrate machine learning, originally done throught matchboxes the basic idea is that the
machine makes random moves and based on the result the probabilities are modified. I wanted to make the learner genereic, so it
theoretically could learn to play any turn based game, maybe with some tweaking of parameters.

### Why Python?
Im not a CS student so don't know many languages...yet

### Why not train against a perfect machine?
Since TicTacToe is solved, a perfect machine will never win, and therefore the trainer.

### Why not remove the spaces and brackets in the strategy object's keys?
Not a logistical choice but more that I liked the idea that the training player had the least amount of idea whats going on, so it
can't do that. Agian not a logical choice.

### Does it work?
To be honest, not yet, I have been able to beat a trained player. Ideally once I can find a perfect dataset of all games I can test it properly,
right now I can only use random games and statistics

### Where now?
When I return to this I will be tackilng things I have raised issues for.
