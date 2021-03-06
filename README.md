# AI Learning to play Flappy Bird using Evolution Strategies

This AI agent uses Evolutional Strategies and deep learning models to master the Flappy Bird game.

Read [Evolution Strategies as a Scalable Alternative to Reinforcement Learning](https://blog.openai.com/evolution-strategies/) from OpenAI if you are interested.

After a few hundred iterations, it masters the game.


![demo](http://uupload.ir/files/ze4o_ezgif.com-gif-maker.gif)

# Dependencies

- [evostra](https://github.com/alirezamika/evostra)
- [PyGame-Learning-Environment](https://github.com/ntasfi/PyGame-Learning-Environment)


# Usage

To see the agent playing the game:

```
from flappy import *

agent = Agent()

# the pre-trained weights are saved into 'weights.pkl' which you can use.
agent.load('weights.pkl')

# play one episode
agent.play(1)
```

To start training the agent:

```
# train for 100 iterations
agent.train(100)
```
