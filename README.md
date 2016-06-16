# Deep Reinforcement Learning Papers

A list of papers and resources dedicated to deep reinforcement learning.

Please note that this list is currently work-in-progress and far from complete.

## TODOs

 - Add more and more papers
 - Improve the way of classifying papers (tags may be useful)
 - Create a policy of this list: curated or comprehensive, how to define "deep reinforcement learning", etc.

## Contributing

If you want to inform the maintainer of a new paper, feel free to contact [@mooopan](https://twitter.com/mooopan). Issues and PRs are also welcome.

## Table of Contents

 - [Papers](#papers)
 - [Talks/Slides](#talksslides)
 - [Miscellaneous](#miscellaneous)

## Papers

 - [Deep Value Function](#deep-value-function)
 - [Deep Policy](#deep-policy)
 - [Deep Actor-Critic](#deep-actor-critic)
 - [Deep Model](#deep-model)
 - [Application to Non-RL Tasks](#application-to-non-rl-tasks)
 - [Unclassified](#unclassified)

### Deep Value Function

 - S. Lange and M. Riedmiller, **Deep Learning of Visual Control Policies**, ESANN, 2010. [pdf](https://www.elen.ucl.ac.be/Proceedings/esann/esannpdf/es2010-87.pdf)
   - Deep Fitted Q-Iteration (DFQ)
 - V. Mnih, K. Kavukcuoglu, D. Silver, A. Graves, I. Antonglou, D. Wierstra, and M. Riedmiller, **Playing Atari with Deep Reinforcement Learning**, NIPS 2013 Deep Learning Workshop, 2013. [pdf](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)
   - Deep Q-Network (DQN) with experience replay
 - V. Mnih, K. Kavukcuoglu, D. Silver, A. a Rusu, J. Veness, M. G. Bellemare, A. Graves, M. Riedmiller, A. K. Fidjeland, G. Ostrovski, S. Petersen, C. Beattie, A. Sadik, I. Antonoglou, H. King, D. Kumaran, D. Wierstra, S. Legg, and D. Hassabis, **Human-level control through deep reinforcement learning**, Nature, 2015. [pdf](http://home.uchicago.edu/~arij/journalclub/papers/2015_Mnih_et_al.pdf) [code](https://sites.google.com/a/deepmind.com/dqn/)
   - Deep Q-Network (DQN) with experience replay and target network
 - T. Schaul, D. Horgan, K. Gregor, and D. Silver, **Universal Value Function Approximators**, ICML, 2015. [pdf](http://schaul.site44.com/publications/uvfa.pdf)
 - A. Nair, P. Srinivasan, S. Blackwell, C. Alcicek, R. Fearon, A. De Maria, M. Suleyman, C. Beattie, S. Petersen, S. Legg, V. Mnih, and D. Silver, **Massively Parallel Methods for Deep Reinforcement Learning**, ICML Deep Learning Workshop, 2015. [pdf](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Publications_files/gorila.pdf)
   - Gorila (General Reinforcement Learning Architecture)
 - K. Narasimhan, T. Kulkarni, and R. Barzilay, **Language Understanding for Text-based Games Using Deep Reinforcement Learning**, EMNLP, 2015. [pdf](http://people.csail.mit.edu/karthikn/pdfs/mud-play15.pdf) [supplementary](http://people.csail.mit.edu/karthikn/pdfs/mud-supp.pdf) [code](http://people.csail.mit.edu/karthikn/mud-play/)
   - LSTM-DQN
 - M. Hausknecht and P. Stone, **Deep Recurrent Q-Learning for Partially Observable MDPs**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1507.06527) [code](https://github.com/mhauskn/dqn/tree/recurrent)
 - M. Lai, **Giraffe: Using Deep Reinforcement Learning to Play Chess**, arXiv. 2015. [arXiv](http://arxiv.org/abs/1509.01549) [code](https://bitbucket.org/waterreaction/giraffe)
 - H. van Hasselt, A. Guez, and D. Silver, **Deep reinforcement learning with double q-learning**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1509.06461)
   - Double DQN
 - F. Zhang, J. Leitner, M. Milford, B. Upcroft, and P. Corke, **Towards Vision-Based Deep Reinforcement Learning for Robotic Motion Control**, in ACRA, 2015. [pdf](http://juxi.net/papers/others/zhang2015acra-submission.pdf)
 - T. Schaul, J. Quan, I. Antonoglou, and D. Silver, **Prioritized Experience Replay**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1511.05952)
 - Z. Wang, N. de Freitas, and M. Lanctot, **Dueling Network Architectures for Deep Reinforcement Learning**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1511.06581)
 - V. François-Lavet, R. Fonteneau, and D. Ernst, **How to Discount Deep Reinforcement Learning: Towards New Dynamic Strategies**, NIPS Deep Reinforcement Learning Workshop, 2015. [arXiv](http://arxiv.org/abs/1512.02011)
 - I. Sorokin, A. Seleznev, M. Pavlov, A. Fedorov, and A. Ignateva, **Deep Attention Recurrent Q-Network**, NIPS Deep Reinforcement Learning Workshop, 2015. [arXiv](http://arxiv.org/abs/1512.01693)
 - A. A. Rusu, S. G. Colmenarejo, C. Gulcehre, G. Desjardins, J. Kirkpatrick, R. Pascanu, V. Mnih, K. Kavukcuoglu, and R. Hadsell, **Policy Distillation**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1511.06295)
 - M. G. Bellemare, G. Ostrovski, A. Guez, P. S. Thomas, and R. Munos, **Increasing the Action Gap: New Operators for Reinforcement Learning**, AAAI, 2016. [arXiv](http://arxiv.org/abs/1512.04860)
 - D. Silver, A. Huang, C. J. Maddison, A. Guez, L. Sifre, G. Van Den Driessche, J. Schrittwieser, I. Antonoglou, V. Panneershelvam, M. Lanctot, S. Dieleman, D. Grewe, J. Nham, N. Kalchbrenner, I. Sutskever, T. Lillicrap, M. Leach, K. Kavukcuoglu, T. Graepel, and D. Hassabis, **Mastering the game of Go with deep neural networks and tree search**, Nature, 2016. [pdf](https://storage.googleapis.com/deepmind-data/assets/papers/deepmind-mastering-go.pdf)
 - T. Zahavy, N. Ben Zrihem, and S. Mannor, **Graying the black box: Understanding DQNs**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1602.02658)
 - J. N. Foerster, Y. M. Assael, N. de Freitas, and S. Whiteson, **Learning to Communicate to Solve Riddles with Deep Distributed Recurrent Q-Networks**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1602.02672)
 - I. Osband, C. Blundell, A. Pritzel, and B. Van Roy, **Deep Exploration via Bootstrapped DQN**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1602.04621)
 - T. Salimans and D. P. Kingma, **Weight Normalization : A Simple Reparameterization to Accelerate Training of Deep Neural Networks**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1602.07868)
 - S. Gu, T. Lillicrap, I. Sutskever, and S. Levine, **Continuous Deep Q-Learning with Model-based Acceleration**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1603.00748)
 - J. Heinrich and D. Silver, **Deep Reinforcement Learning from Self-Play in Imperfect-Information Games**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1603.01121)
 - T. D. Kulkarni, K. R. Narasimhan, A. Saeedi, and J. B. Tenenbaum, **Hierarchical Deep Reinforcement Learning: Integrating Temporal Abstraction and Intrinsic Motivation**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1604.06057)
 - J. Oh, V. Chockalingam, S. Singh, and H. Lee, **Control of Memory, Active Perception, and Action in Minecraft**, ICML, 2016. [arXiv](http://arxiv.org/abs/1605.09128)
 - T. D. Kulkarni, A. Saeedi, S. Gautam, and S. J. Gershman, **Deep Successor Reinforcement Learning**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1606.02396)

### Deep Policy

 - S. Levine, C. Finn, T. Darrell, and P. Abbeel, **End-to-End Training of Deep Visuomotor Policies**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1504.00702)
   - partially observed guided policy search
 - J. Schulman, S. Levine, P. Moritz, M. Jordan, and P. Abbeel, **Trust Region Policy Optimization**, ICML, 2015. [pdf](http://jmlr.org/proceedings/papers/v37/schulman15.pdf)
 - T. Zhang, G. Kahn, S. Levine, and P. Abbeel, **Learning Deep Control Policies for Autonomous Aerial Vehicles with MPC-Guided Policy Search**, ICRA, 2016. [arXiv](http://arxiv.org/abs/1509.06791)

### Deep Actor-Critic

 - J. Schulman, P. Moritz, S. Levine, M. Jordan, and P. Abbeel, **High-Dimensional Continuous Control Using Generalized Advantage Estimation**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1506.02438)
 - T. P. Lillicrap, J. J. Hunt, A. Pritzel, N. Heess, T. Erez, Y. Tassa, D. Silver, and D. Wierstra, **Continuous control with deep reinforcement learning**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1509.02971)
 - D. Balduzzi and M. Ghifary, **Compatible Value Gradients for Reinforcement Learning of Continuous Deep Policies**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1509.03005)
 - M. Hausknecht and P. Stone, **Deep Reinforcement Learning in Parameterized Action Space**, arXiv. 2015. [arXiv](http://arxiv.org/abs/1511.04143)
 - N. Heess, J. J. Hunt, T. P. Lillicrap, and D. Silver, **Memory-based control with recurrent neural networks**, NIPS Deep Reinforcement Learning Workshop, 2015. [arXiv](http://arxiv.org/abs/1512.04455)
 - V. Mnih, A. P. Badia, M. Mirza, A. Graves, T. P. Lillicrap, T. Harley, D. Silver, and K. Kavukcuoglu, **Asynchronous Methods for Deep Reinforcement Learning**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1602.01783)

### Deep Model

 - B. C. Stadie, S. Levine, and P. Abbeel, **Incentivizing Exploration In Reinforcement Learning With Deep Predictive Models**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1507.00814)
 - J. Oh, X. Guo, H. Lee, R. Lewis, and S. Singh, **Action-Conditional Video Prediction using Deep Networks in Atari Games**, NIPS, 2015. [arXiv](http://arxiv.org/abs/1507.08750)
 - J. M. Assael, W. Om, T. B. Schön, and M. P. Deisenroth, **Data-Efficient Learning of Feedback Policies from Image Pixels using Deep Dynamical Models**, arXiv, 2015 [arXiv](http://arxiv.org/abs/1510.02173)
 - N. Heess, G. Wayne, D. Silver, T. Lillicrap, Y. Tassa, and T. Erez, **Learning Continuous Control Policies by Stochastic Value Gradients**, NIPS, 2015. [arXiv](http://arxiv.org/abs/1510.09142) [video](https://www.youtube.com/watch?v=PYdL7bcn_cM)
 - J. Schmidhuber, **On Learning to Think: Algorithmic Information Theory for Novel Combinations of Reinforcement Learning Controllers and Recurrent Neural World Models**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1511.09249)
 - K. Fragkiadaki, P. Agrawal, S. Levine, and J. Malik, **Learning Visual Predictive Models of Physics for Playing Billiards**, ICLR, 2016. [arXiv](http://arxiv.org/abs/1511.07404)

### Application to Non-RL Tasks

- J. C. Caicedo and S. Lazebnik, **Active Object Localization with Deep Reinforcement Learning**, ICCV, 2015. [pdf](http://web.engr.illinois.edu/~slazebni/publications/iccv15_active.pdf)
- H. Guo, **Generating Text with Deep Reinforcement Learning**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1510.09202)
- S. Hansen, **Using Deep Q-Learning to Control Optimization Hyperparameters**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1602.04062)

### Unclassified

 - X. Guo, S. Singh, H. Lee, R. Lewis, and X. Wang, **Deep learning for real-time Atari game play using offline Monte-Carlo tree search planning**, NIPS, 2014. [pdf](http://papers.nips.cc/paper/5421-deep-learning-for-real-time-atari-game-play-using-offline-monte-carlo-tree-search-planning.pdf) [video](https://sites.google.com/site/nips2014atari/)
 - S. Mohamed and D. J. Rezende, **Variational Information Maximisation for Intrinsically Motivated Reinforcement Learning**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1509.08731)
 - Y. Liang, M. C. Machado, E. Talvitie, and M. Bowling, **State of the Art Control of Atari Games Using Shallow Reinforcement Learning**, arXiv, 2015. [arXiv](http://arxiv.org/abs/1512.01563)
 - A. Tamar, S. Levine, and P. Abbeel, **Value Iteration Networks**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1602.02867)
 - C. Blundell, G. Deepmind, B. Uria, A. Pritzel, Y. Li, A. Ruderman, J. Z. Leibo, J. Rae, D. Wierstra, and D. Hassabis, **Model-Free Episodic Control**, arXiv, 2016. [arXiv](http://arxiv.org/abs/1606.04460)

## Talks/Slides

 - S. Levine, **Deep Learning for Decision Making and Control**, 2015. [video](https://www.youtube.com/watch?v=EtMyH_--vnU)
 - D. Silver, **Deep Reinforcement Learning**, ICLR, 2015. [video1](https://www.youtube.com/watch?v=EX1CIVVkWdE) [video2](https://www.youtube.com/watch?v=zXa6UFLQCtg) [slides](http://www.iclr.cc/lib/exe/fetch.php?media=iclr2015:silver-iclr2015.pdf)
 - D. Silver, **Deep Reinforcement Learning**, UAI, 2015. [video](https://www.youtube.com/watch?v=qLaDWKd61Ig)

## Miscellaneous

 - [Deep Q-Learning - Google Group](https://groups.google.com/forum/#!forum/deep-q-learning)
 - [CS 294 Deep Reinforcement Learning, Fall 2015](http://rll.berkeley.edu/deeprlcourse/)
 - [Deep Reinforcement Learning Workshop, NIPS 2015](http://rll.berkeley.edu/deeprlworkshop/)
 - [junhyukoh/deep-reinforcement-learning-papers](https://github.com/junhyukoh/deep-reinforcement-learning-papers)
 - [DeepMind's Nature Paper and Earlier Related Work](http://people.idsia.ch/~juergen/naturedeepmind.html)

