# 2021-KAIST-Include-AlphaZero

2021-KAIST-Include-AlphaZero is the material(lecture notes, examples and assignments) repository for making AI of the game 'Go' using [AlphaZero](https://deepmind.com/blog/article/alphazero-shedding-new-light-grand-games-chess-shogi-and-go) course that I'll teach the club 'Include' at KAIST in the spring of 2021. Note that examples and assignments in this repository uses [TensorFlow](https://www.tensorflow.org/) and [PyTorch](https://pytorch.org/).

## Book

Deep Learning and the Game of Go, by Max Pumperla and Kevin Ferguson (Manning, 2019)
- Korean: 딥러닝과 바둑 (한빛미디어, 2020)

![](https://images.manning.com/360/480/resize/book/8/4ef97d9-3867-4f76-9301-c05009020c68/Pumperla-DL-HI.png)

## Contents

- Week 1 (3/20)
  - Toward deep learning: a machine-learning introduction
    - What is machine learning?
    - Machine learning by example
    - Deep learning
    - What you will learn in this lecture
  - Go as a machine-learning problem
    - Why games?
    - A lightning introduction to the game of Go
    - Handicaps
    - Where to learn more
    - What can we tech a machine?
    - How to measure our Go AI's strength
- Week 2 (3/27)
  - Implementing your first Go bot
    - Representing a game of Go in Python
    - Go game state and checking for illegal moves
    - Ending a game
    - Creating your first bot: the weakest Go AI imaginable
    - Speeding up gameplay with Zobrist hashing
    - Playing against your bot
- Week 3 (4/3)
  - Playing games with tree search
    - Classsifying games
    - Anticipating your opponent with minimax search
    - Solving tic-tae-toe: a minimax example
    - Reducing search space with pruning
    - Evaluating game states with the Monte Carlo tree search algorithm
- Week 4 (4/10)
  - No lecture due to mid-term exam
- Week 5 (4/17)
  - No lecture due to mid-term exam
- Week 6 (4/24)
  - Getting started with neural networks
    - A simple use case: Classifying handwritten digits
    - The basics of neural networks
    - Feed-forward networks
    - How good are our predictions? Loss functions and optimization
    - Training a neural network step-by-step in Python
- Week 7 (5/1)
  - Designing a neural network for Go data
    - Encoding a Go game position for neural networks
    - Generating tree-search games as network training data
    - TensorFlow 2.0 and PyTorch: Deep-learning libraries
    - Analyzing space with convolutional networks
    - Predicting Go move probabilities
    - Building deeper networks with dropout and rectified linear units
    - Putting it all together for a stronger Go move prediction network
- Week 8 (5/8)
  - Learning from data: a deep learning bot
    - Importing Go game records
    - Preparing Go data for deep learning
    - Training a deep-learning model on human game-play data
    - Building more-realistic Go data encoders
    - Training efficiently with adaptive gradients
    - Running your own experiments and evaluating performance
- Week 9 (5/15)
  - Learning by practice: reinforcement learning
    - The reinforcement-learning cycle
    - What goes into experience?
    - Building an agent that can learn
    - Self-play: how a computer program practices
- Week 10 (5/22)
  - Reinforcement learning with policy gradients
    - How random games can identify good decisions
    - Modifying neural network policies with gradient descent
    - Tips for training with self-play
  - Reinforcement learning with value methods
    - Playing games with Q-learning
    - Q-learning with TensorFlow 2.0 and PyTorch
- Week 11 (5/29)
  - Reinforcement learning with actor-critic methods
    - Advantage tells you which decisions are important
    - Designing a neural network for actor-critic learning
    - Playing games with an actor-critic agent
    - Training an actor-critic agent from experience data
- Week 12 (6/5)
  - No lecture due to mid-term exam
- Week 13 (6/12)
  - No lecture due to mid-term exam
- Week 14 (6/19)
  - AlphaGo: Bringing it all together
    - Training deep neural networks for AlphaGo
    - Bootstrapping self-play from policy networks
    - Deriving a value network from self-play data
    - Better search with policy and value networks
    - Practical considerations for training your own AlphaGo
- Week 15 (6/26)
  - AlphaGo Zero: Integrating tree search with reinforcement learning
    - Building a neural network for tree search
    - Tree search
    - Training
    - Improving exploration with Dirichlet noise
    - Modern techniques for deeper neural networks
    - Additional resources
    - Wrapping up

## How To Contribute

Contributions are always welcome, either reporting issues/bugs or forking the repository and then issuing pull requests when you have completed some additional coding that you feel will be beneficial to the main project. If you are interested in contributing in a more dedicated capacity, then please contact me.

## Contact

You can contact me via e-mail (utilForever at gmail.com). I am always happy to answer questions or help with any issues you might have, and please be sure to share any additional work or your creations with me, I love seeing what other people are making.

## License

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2021 [Chris Ohk](http://www.github.com/utilForever).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
