##Reinforcement Learning

###Algorithm
- DQN ( Deep Q-Learing )
- Q-learning
- Policy Gradient
- A3C ( Asynchronous Advanced Actor-Critic )
- MDP (Markov Decision process)
- OO-MDP (Object-oriented Markov Decision Process)
- Gym

###Lecture & Books
- [CS188 2013](https://www.youtube.com/user/CS188Spring2013)
- [CS188 2014](https://www.youtube.com/watch?v=IXuHxkpO5E8)
- [CS188 2016](https://www.youtube.com/watch?v=3aCn2-Slaoc&list=PLIeooNSdhQE5kRrB71yu5yP9BRCJCSbMt)
- David Sliver (Deep Mind)
- [John Schulman](https://www.youtube.com/watch?v=aUrX-rP_ss4&index=1&list=PLUdqnrHmtdXQuivfwPyEKi3y5eQJqo1c4)
- Udacity - Reinforcement Learning
- [sutton book 2015 ](https://www.dropbox.com/s/b3psxv2r0ccmf80/book2015oct.pdf?dl=0)
- Replicating Deep Q Learning with TensorFlow 
  - [1](https://www.youtube.com/watch?v=suNNrEHDR-I) / [2](https://www.youtube.com/watch?v=Zu-oNPPVvfI)
- [Policy Gradients wiki](http://www.scholarpedia.org/article/Policy_gradient_methods)


### Posting
- [Deep Mind blog](https://deepmind.com/blog)
- [Open Ai 분석-모두의 연구소](http://www.modulabs.co.kr/RL_library/2621)
- [Replicating Deep Q Learning with TensorFlow - 한국어](https://www.youtube.com/watch?v=suNNrEHDR-I)
- [Simple reinforcement learning ](http://kvfrans.com/simple-algoritms-for-solving-cartpole/)
- [GP By karpathy](http://karpathy.github.io/2016/05/31/rl/)
- [Deep Reinforcement Learning: Frontiers and Challenges, IJCAI 2016](https://sites.google.com/site/deeprlijcai16/programme)
- [dueling_dqn](http://torch.ch/blog/2016/04/30/dueling_dqn.html)
- [torch blog](http://torch.ch/blog/index.html)
- [Reinforce Pong at Gym-tensorflowKorea](https://tensorflowkorea.wordpress.com/2016/07/13/reinforce-pong-at-gym/)
- [Q-learing + CNN를 이용한 지역화](http://www.slideshare.net/ssuser06e0c5/q-learning-cnn-object-localization)
- Reinforment L 
  - [1. Demystifying Deep Reinforcement Learning](https://www.nervanasys.com/demystifying-deep-reinforcement-learning/)
  - [2. deep-reinforcement-learning-with-neon](https://www.nervanasys.com/deep-reinforcement-learning-with-neon/)
  - [3. Deep Reinforcement Learning with OpenAI Gym](https://www.nervanasys.com/openai/)


###Paper
- DeepMind Papers : https://deepmind.com/publications.html
- Learn Mario playing : Evolving Neural Networks through Augmenting Topologies - http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf
- Playing Atari : Playing Atari with Deep Reinforcement Learning(DQN) - http://arxiv.org/abs/1312.5602
- Play FlappyBird( DQN imp ) - http://sarvagyavaish.github.io/FlappyBirdRL/
- [Dueling Network Architectures for Deep Reinforcement Learning](http://arxiv.org/pdf/1511.06581v3.pdf)
- [DeepMind-Early Visual Concept Learning with Unsupervised Deep Learning](https://arxiv.org/pdf/1606.05579.pdf)
- [DeepMind-Conditional Image Generation with PixelCNN Decoders](https://arxiv.org/pdf/1606.05579.pdf)
- [DeepMind-Asynchronous Methods for Deep Reinforcement Learning](http://arxiv.org/pdf/1602.01783.pdf)
- [DeepMind-Continuous Deep q-Learning with Model-based Acceleration](http://arxiv.org/pdf/1603.00748v1.pdf)
  - [구현](https://github.com/carpedm20/NAF-tensorflow)
  - 논문에서 비교하고 있는 Deep Deterministic Policy Gradient (DDPG)는 Continuous space에서 actor-critic을 사용해서 문제를 해결했는데, 이 논문에서는 duelling network와 유사한 구조를 사용해서 적은 파라미터와 비교적 간단한 알고리즘으로 학습이 가능하다고 합니다. OpenAI에서 공개한 Requests for Research 중에서 하나가 이 논문을 구현하는건데, 이제 hyperparameter를 바꾸지 않고 얼마나 많은 문제를 풀 수 있을지 실험을 해 봐야할 것 같네요.
최근에 supervised learning 문제에 대한 discussion은 많이 보이던데, DeepMind나 OpenAI가 집중하고 있는 RL이나 generative model에 대한 얘기도 좀 더 많이 나오면 좋겠네요 ㅎㅎ 다음에는 이번 ICML에서 best paper를 받은 PixelRNN과 PixelCNN를 공부해 보려고 합니다

###관련 Github
- [tensorflow-딥러닝 논문 구현-By Carpedm20](https://github.com/carpedm20/deep-rl-tensorflow)
- [자료 모음-홍상진](https://github.com/sangjinhong/deep_learning)
- [keras-강화 학습 구현- By matthiasplappert](https://github.com/matthiasplappert/keras-rl)