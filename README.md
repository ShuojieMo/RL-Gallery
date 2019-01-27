# RL Framework
* [Spinning Up, OpenAI](https://spinningup.openai.com/)
* [Rllab, Berkeley RL Lab](https://github.com/rll/rllab)
* [Rllib, UC Berkeley’s RISE Lab, Ray Project](https://github.com/ray-project/ray/tree/master/python/ray/rllib/)
* [Rlkit, Vitchyr Pong's Implementations](https://github.com/vitchyr/rlkit)
* [Baselines, OpenAI](https://github.com/openai/baselines)
* [Gym, OpenAI](https://gym.openai.com/docs/)
* [Universe, OpenAI](https://blog.openai.com/universe/)
* [Roboschool, OpenAI](https://github.com/openai/roboschool)
* [Reaver, StarCraft II](https://github.com/inoryy/reaver-pysc2)
* [TensorForce](https://github.com/reinforceio/tensorforce)
* [Keras RL](https://github.com/keras-rl/keras-rl)
* [Dopamine, Google](https://github.com/google/dopamine)
* [Coach, Intel](https://github.com/NervanaSystems/coach)
* [PARL, Baidu](https://github.com/PaddlePaddle/PARL)

# RL Tutorials & Blogs
* [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/bookdraft2017nov5.pdf)
* [CS 294-112, UC Berkeley](http://rail.eecs.berkeley.edu/deeprlcourse/)
* [David Silver's courses](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
* [MIT 6.S094: Deep Learning for Self-Driving Cars 2018 Lecture 3 Notes: Deep Reinforcement Learning](https://hackernoon.com/mit-6-s094-deep-learning-for-self-driving-cars-2018-lecture-3-notes-deep-reinforcement-learning-fe9a8592e14a)
* [UCL Advanced Deep Learning & Reinforcement Learning](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs)
* [An Introduction to Deep Reinforcement Learning](https://arxiv.org/pdf/1811.12560v2.pdf)
* [Morvan Reinforcement Learning](https://morvanzhou.github.io/tutorials/machine-learning/reinforcement-learning/)
* [PyTorch tutorials of RL](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html)
* [Arthur Juliani's blog](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0)
* [Thomas Simonini's DRL course](https://www.simoninithomas.com/)
* [Lilian Weng's blog](https://lilianweng.github.io/lil-log/2018/02/19/a-long-peek-into-reinforcement-learning.html)
* [Andrej Karpathy's blog](http://karpathy.github.io/2016/05/31/rl/)

# RL Implementation
* [RL-Adventure, Dulat Yerzat's Implementation](https://github.com/higgsfield/RL-Adventure)
* [RL-Adventure2, Dulat Yerzat's Implementation](https://github.com/higgsfield/RL-Adventure-2)
* [John Schulman's RL repository](https://github.com/joschu/modular_rl)
* [TD3 Implementation](https://github.com/sfujim/TD3)
* [SAC Implementation](https://github.com/haarnoja/sac)
* [Denny Britz's Implementations](https://github.com/dennybritz/reinforcement-learning)
* [ShangtongZhang's implementations](https://github.com/ShangtongZhang/DeepRL)
* [DeepPILCO, zuoxingdong's implementation](https://github.com/zuoxingdong/DeepPILCO)
* [Morvan Zhou's Implementations](https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow)

# RL Papers
* [Model-based-papers](https://github.com/danfeiX/model-based-papers)
* [DRL papers 2015-2016](https://github.com/junhyukoh/deep-reinforcement-learning-papers)
* [Spinning up, OpenAI](https://spinningup.openai.com/en/latest/spinningup/keypapers.html)

# RL Applications
* [Play Atari games, DeepMind](https://arxiv.org/pdf/1312.5602v1.pdf)
* [AlphaGo & AlphaGoZero, playing Go, DeepMind](https://deepmind.com/research/alphago/)
* [AlphaStar, playing StarCraft2, DeepMind](https://deepmind.com/blog/alphastar-mastering-real-time-strategy-game-starcraft-ii/)
* [Autonomous helicopter flight, Stanford University](http://heli.stanford.edu/)
* [Skill learning in 3D simulator, Xue Bin Peng](https://arxiv.org/pdf/1804.02717.pdf)
* [Agile locomotion for quadruped robots, Jie Tan](https://arxiv.org/pdf/1804.10332.pdf)
* [ANYmal robot skill learning, Synced](https://syncedreview.com/2019/01/23/you-cant-keep-an-rl-powered-anymal-down/)
* [Modular legged robot skill learning, Disney Research](https://www.disneyresearch.com/publication/automated-deep-reinforcement-learning-environment-for-hardware-of-a-modular-legged-robot/)
* [RL in business (Chinese version), Alibaba](http://techforum-img.cn-hangzhou.oss-pub.aliyun-inc.com/1517812754285/reinforcement_learning.pdf)
* [LOXM, executing trades, J.P.Morgan](https://www.jpmorgan.com/global/LOXM)

# RL Technique

| Technique                 | Benefit                                   | First Mentioned Key Algorithm      |
| ------------------------- | ----------------------------------------- | ---------------------------------- |
| Target network            | Stabilize the training process            | DQN, 2015                          |
| Memory buffer             | Breaking data relevance                   | DQN, 2015                          |
| KL-constrained update     | Optimize update step size                 | TRPO, 2015                         |
| Advantage function        | Stabilize learning                        | A3C, 2015                          |
| Importance sampling       | Data efficient                            | Prioritized Experience Replay,2016 |
| Entropy-regularized       | Better exploration                        | Soft Q-Learning, 2017              |
| Boltzmann policy          | Richer mathematical meaning               | Soft Q-Learning, 2017              |
| Target policy smoothing   | Avert Q-function incorrect sharp peak     | TD3, 2018                          |
| Clipped double-Q learning | Fend off overestimation in the Q-function | TD3, 2018                          |
| Reparameterize the policy | Lower variance estimate                   | SAC, 2018                          |