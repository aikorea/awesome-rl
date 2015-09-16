# Awesome Reinforcement Learning

A curated list of resources dedicated to reinforcement learning.

We have pages for other topics: [awesome-rnn](http://jiwonkim.org/awesome-rnn), [awesome-deep-vision](http://jiwonkim.org/awesome-deep-vision/), [awesome-random-forest](http://jiwonkim.org/awesome-random-forest/)


## Contributing
Please feel free to [pull requests](https://github.com/aikorea/awesome-rl/pulls)

## Table of Contents

 - [Codes](#codes)
 - [Theory](#theory)
   - [Lectures](#lectures)
   - [Books / Thesis](#books--thesis)
   - [Surveys](#surveys)
 - [Applications](#applications)
   - [Game Playing](#game-playing)
   - [Robotics](#robotics)
 - [Datasets](#datasets)
 - [Tutorials](#tutorials)
 - [Online Demos](#online-demos)

## Codes
 - Codes for examples and exercises in Richard Sutton and Andrew Barto's Reinforcement Learning: An Introduction
  - [MATLAB Code](http://waxworksmath.com/Authors/N_Z/Sutton/sutton.html)
  - [C/Lisp Code](https://webdocs.cs.ualberta.ca/~sutton/book/code/code.html) 
  - [Book](http://webdocs.cs.ualberta.ca/~sutton/book/ebook/the-book.html) 
 - Simulation code for Reinforcement Learning Control Problems
  - [Pole-Cart Problem](http://pages.cs.wisc.edu/~finton/poledriver.html)
  - [Q-learning Controller](http://pages.cs.wisc.edu/~finton/qcontroller.html)
 - [MATLAB Environment and GUI for Reinforcement Learning](http://www.cs.colostate.edu/~anderson/res/rl/matlabpaper/rl.html)
 - [Reinforcement Learning Repository - University of Massachusetts, Amherst](http://www-anw.cs.umass.edu/rlr/)
 - [Brown-UMBC Reinforcement Learning and Planning Library (Java)](http://burlap.cs.brown.edu/)
 - [Reinforcement Learning in R (MDP, Value Iteration)](http://www.statsblogs.com/2014/01/07/reinforcement-learning-in-r-markov-decision-process-mdp-and-value-iteration/) 
 - [Reinforcement Learning Environment in Python and MATLAB](https://jamh-web.appspot.com/download.htm)
 - [RL-Glue](http://glue.rl-community.org/wiki/Main_Page) (standard interface for RL) and [RL-Glue Library](http://library.rl-community.org/wiki/Main_Page)

## Theory

### Lectures

 - [UCL] [COMPM050/COMPGI13 Reinforcement Learning by David Silver](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
 - [UC Berkeley] CS188 Artificial Intelligence by Pieter Abbeel
   - [Lecture 8: Markov Decision Processes 1](https://www.youtube.com/watch?v=i0o-ui1N35U)
   - [Lecture 9: Markov Decision Processes 2](https://www.youtube.com/watch?v=Csiiv6WGzKM)
   - [Lecture 10: Reinforcement Learning 1](https://www.youtube.com/watch?v=ifma8G7LegE)
   - [Lecture 11: Reinforcement Learning 2](https://www.youtube.com/watch?v=Si1_YTw960c)
 - [Udacity (Georgia Tech.)] [Machine Learning 3: Reinforcement Learning (CS7641)](https://www.udacity.com/course/machine-learning-reinforcement-learning--ud820)
 

### Books / Thesis
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction [[Book]](http://webdocs.cs.ualberta.ca/~sutton/book/ebook/the-book.html) [[Code]](https://webdocs.cs.ualberta.ca/~sutton/book/code/code.html)
 - Csaba Szepesvari, Algorithms for Reinforcement Learning [[Book]](http://www.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
 - David Poole and Alan Mackworth, Artificial Intelligence: Foundations of Computational Agents [[Book Chapter]](http://artint.info/html/ArtInt_262.html)

 
### Surveys 
 - Leslie Pack Kaelbling, Andrew W. Moore, Reinforcement Learning: A Survey, JAIR, 1996. [[Paper]](https://www.jair.org/media/301/live-301-1562-jair.pdf) 
 - Jens Kober, J. Andrew Bagnell, Jan Peters, Reinforcement Learning in Robotics, A Survey, IJRR, 2013. [[Paper]](http://www.ias.tu-darmstadt.de/uploads/Publications/Kober_IJRR_2013.pdf)
 - Littman, Michael L. "Reinforcement learning improves behaviour from evaluative feedback." Nature 521.7553 (2015): 445-451. [[Paper]](http://www.nature.com/nature/journal/v521/n7553/full/nature14540.html)

## Applications
### Game Playing
  - TD-Gammon (Back-Gammon game play using TD(λ))[[paper]](http://www.bkgm.com/articles/tesauro/tdl.html)
  - Human-level control through deep reinforcement learning, Nature (2015) [[Paper]](http://www.readcube.com/articles/10.1038%2Fnature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D) [[Code]](https://sites.google.com/a/deepmind.com/dqn/) [[Video]](https://www.youtube.com/watch?v=iqXKQf2BOSE)
  - [Flappy Bird Reinforcement Learning](https://github.com/SarvagyaVaish/FlappyBirdRL) [[Video]](https://www.youtube.com/watch?v=xM62SpKAZHU)
  - MarI/O (learning to play Mario with evolutionary reinforcement learning using artificial neural networks) [[Paper]](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf)[[Video]](https://www.youtube.com/watch?v=qv6UVOQ0F44)

### Robotics
   - Robot Motor SKill Coordination with EM-based Reinforcement Learning (IROS 2010) [[Paper]](http://kormushev.com/papers/Kormushev-IROS2010.pdf) [[Video]](https://www.youtube.com/watch?v=W_gxLKSsSIE)
   - Autonomous Skill Acquisition on a Mobile Manipulator (AAAI 2011) [[Paper]](https://www.youtube.com/watch?v=yUICAkSQTZY) [[Video]](https://www.youtube.com/watch?v=yUICAkSQTZY)
   - Efficient Reinforcement Learning for Robots using Informative Simulated Priors (ICRA 2015) [[Paper]](http://markjcutler.com/papers/Cutler15_ICRA.pdf) [[Video]](https://www.youtube.com/watch?v=kKClFx6l1HY)
   - An Application of Reinforcement Learning to Aerobatic Helicopter Flight (NIPS 2006) [[Paper]](http://heli.stanford.edu/papers/nips06-aerobatichelicopter.pdf) [[Video]](https://www.youtube.com/watch?v=VCdxqn0fcnE)
   - Generalized Model Learning for Reinforcement Learning on a Humanoid Robot (ICRA 2010) [[Paper]](https://ccc.inaoep.mx/~mdprl/documentos/Hester_2010.pdf) [[Video]](https://www.youtube.com/watch?v=mRpX9DFCdwI&list=PL5nBAYUyJTrM48dViibyi68urttMlUv7e&index=12)

## Datasets 

## Tutorials
  - Mance Harmon and Stephanie Harmon, [Reinforcement Learning: A Tutorial](http://old.nbu.bg/cogs/events/2000/Readings/Petrov/rltutorial.pdf)
  - UNSW - [Reinforcement Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/index.html)
   - [Introduction](http://www.cse.unsw.edu.au/~cs9417ml/RL1/introduction.html) 
   - [TD-Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/tdlearning.html)
   - [Q-Learning and SARSA](http://www.cse.unsw.edu.au/~cs9417ml/RL1/algorithms.html)
   - [Applet for "Cat and Mouse" Game](http://www.cse.unsw.edu.au/~cs9417ml/RL1/applet.html) 
  - [ROS Reinforcement Learning Tutorial](http://wiki.ros.org/reinforcement_learning/Tutorials/Reinforcement%20Learning%20Tutorial)
  - [POMDP for Dummies](http://cs.brown.edu/research/ai/pomdp/tutorial/index.html)

## Online Demos
 - [blank](blank)
