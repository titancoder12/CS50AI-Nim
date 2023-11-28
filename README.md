# [CS50AI Week 4, Learning](https://cs50.harvard.edu/ai/2023/weeks/4/) - [Nim](https://cs50.harvard.edu/ai/2023/projects/4/nim/)

An AI that teaches itself to play Nim through reinforcement learning.

## Summary
In the game Nim, we begin with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.

Using Q-learning for this project, we try to learn a reward value (a number) for every (state, action) pair. An action that loses the game will have a reward of -1, an action that results in the other player losing the game will have a reward of 1, and an action that results in the game continuing has an immediate reward of 0, but will also have some future reward.

## Links
[CS50AI Week 4](https://cs50.harvard.edu/ai/2023/weeks/4/)

[CS50AI Week 4 Notes](https://cs50.harvard.edu/ai/2023/notes/4/)

[CS50AI Week 4 Projects](https://cs50.harvard.edu/ai/2023/projects/4/)

[CS50AI Week 4 Projects - Nim](https://cs50.harvard.edu/ai/2023/projects/4/nim/)
