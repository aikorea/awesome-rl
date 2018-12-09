# Awesome Reinforcement Learning  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources dedicated to reinforcement learning.

We have pages for other topics: [awesome-rnn](https://github.com/kjw0612/awesome-rnn), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-random-forest](https://github.com/kjw0612/awesome-random-forest)

Maintainers: [Hyunsoo Kim](http://sites.duke.edu/hyunsookim/), [Jiwon Kim](http://github.com/kjw0612)

We are looking for more contributors and maintainers!


## Contributing
Please feel free to [pull requests](https://github.com/aikorea/awesome-rl/pulls)

## Table of Contents

 - [Codes](#codes)
 - [Theory](#theory)
   - [Lectures](#lectures)
   - [Books](#books)
   - [Surveys](#surveys)
   - [Papers / Thesis](#papers--thesis)
 - [Applications](#applications)
   - [Game Playing](#game-playing)
   - [Robotics](#robotics)
   - [Control](#control)
   - [Operations Research](#operations-research)
   - [Human Computer Interaction](#human-computer-interaction)
 - [Tutorials / Websites](#tutorials--websites)
 - [Online Demos](#online-demos)
 - [Open Source Reinforcement Learning Platforms](#open-source-reinforcement-learning-platforms)

## Codes
 - Codes for examples and exercises in Richard Sutton and Andrew Barto's Reinforcement Learning: An Introduction
    - [Python Code](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
    - [MATLAB Code](http://waxworksmath.com/Authors/N_Z/Sutton/sutton.html)
    - [C/Lisp Code](https://webdocs.cs.ualberta.ca/~sutton/book/code/code.html)
    - [Book](http://webdocs.cs.ualberta.ca/~sutton/book/ebook/the-book.html)
 - Simulation code for Reinforcement Learning Control Problems
    - [Pole-Cart Problem](http://pages.cs.wisc.edu/~finton/poledriver.html)
    - [Q-learning Controller](http://pages.cs.wisc.edu/~finton/qcontroller.html)
 - [MATLAB Environment and GUI for Reinforcement Learning](http://www.cs.colostate.edu/~anderson/res/rl/matlabpaper/rl.html)
 - [Reinforcement Learning Repository - University of Massachusetts, Amherst](http://www-anw.cs.umass.edu/rlr/)
 - [Brown-UMBC Reinforcement Learning and Planning Library (Java)](http://burlap.cs.brown.edu/)
 - [Reinforcement Learning in R (MDP, Value Iteration)](http://www.moneyscience.com/pg/blog/StatAlgo/read/635759/reinforcement-learning-in-r-markov-decision-process-mdp-and-value-iteration)
 - [Reinforcement Learning Environment in Python and MATLAB](https://jamh-web.appspot.com/download.htm)
 - [RL-Glue](http://glue.rl-community.org/wiki/Main_Page) (standard interface for RL) and [RL-Glue Library](http://library.rl-community.org/wiki/Main_Page)
 - [PyBrain Library](http://www.pybrain.org/) - Python-Based Reinforcement learning, Artificial intelligence, and Neural network
 - [RLPy Framework](http://rlpy.readthedocs.org/en/latest/) -  Value-Function-Based Reinforcement Learning Framework for Education and Research
 - [Maja](http://mmlf.sourceforge.net/) - Machine learning framework for problems in Reinforcement Learning in python
 - [TeachingBox](http://servicerobotik.hs-weingarten.de/en/teachingbox.php) - Java based Reinforcement Learning framework
 - [Policy Gradient Reinforcement Learning Toolbox for MATLAB](http://www.ias.informatik.tu-darmstadt.de/Research/PolicyGradientToolbox)
 - [PIQLE](http://sourceforge.net/projects/piqle/) - Platform Implementing Q-Learning and other RL algorithms
 - [BeliefBox](https://code.google.com/p/beliefbox/) - Bayesian reinforcement learning library and toolkit
 - [Deep Q-Learning with TensorFlow](https://github.com/nivwusquorum/tensorflow-deepq) - A deep Q learning demonstration using Google Tensorflow
 - [Atari](https://github.com/Kaixhin/Atari) - Deep Q-networks and asynchronous agents in Torch
 - [AgentNet](https://github.com/yandexdataschool/AgentNet) - A python library for deep reinforcement learning and custom recurrent networks using Theano+Lasagne.
 - [Reinforcement Learning Examples by RLCode](https://github.com/rlcode/reinforcement-learning) - A Collection of minimal and clean reinforcement learning examples
 - [OpenAI Baselines](https://github.com/openai/baselines) - Well tested implementations ([and results](https://github.com/openai/baselines-results)) of reinforcement learning algorithms from OpenAI 
 - [PyTorch Deep RL](https://github.com/ShangtongZhang/DeepRL) - Popular deep RL algorithm implementations with PyTorch
 - [ChainerRL](https://github.com/chainer/chainerrl) - Popular deep RL algorithm implementations with Chainer
 - [Black-DROPS](https://github.com/resibots/blackdrops) - Modular and generic code for the model-based policy search Black-DROPS algorithm (IROS 2017 paper) and easy integration with the [DART](http://dartsim.github.io/) simulator

## Theory

### Lectures
 - [UCL] [COMPM050/COMPGI13 Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html) by David Silver
 - [UC Berkeley] CS188 Artificial Intelligence by Pieter Abbeel
   - [Lecture 8: Markov Decision Processes 1](https://www.youtube.com/watch?v=i0o-ui1N35U)
   - [Lecture 9: Markov Decision Processes 2](https://www.youtube.com/watch?v=Csiiv6WGzKM)
   - [Lecture 10: Reinforcement Learning 1](https://www.youtube.com/watch?v=ifma8G7LegE)
   - [Lecture 11: Reinforcement Learning 2](https://www.youtube.com/watch?v=Si1_YTw960c)
 - [Udacity (Georgia Tech.)] [CS7642 Reinforcement Learning](https://classroom.udacity.com/courses/ud600)
 - [Stanford] [CS229 Machine Learning - Lecture 16: Reinforcement Learning](https://www.youtube.com/watch?v=RtxI449ZjSc&feature=relmfu) by Andrew Ng
 - [UC Berkeley] [Deep RL Bootcamp](https://sites.google.com/view/deep-rl-bootcamp/lectures)
 - [UC Berkeley] [CS294 Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/) by John Schulman and Pieter Abbeel
 - [CMU] [10703: Deep Reinforcement Learning and Control, Spring 2017](https://katefvision.github.io/)
 - [MIT] [6.S094: Deep Learning for Self-Driving Cars](http://selfdrivingcars.mit.edu/)
   - [Lecture 2: Deep Reinforcement Learning for Motion Planning](https://www.youtube.com/watch?v=QDzM8r3WgBw&list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)
 - [Siraj Raval]: Introduction to AI for Video Games (Reinforcement Learning Video Series)
   - [Introduction to AI for video games](https://youtu.be/i_McNBDP9Qs)
   - [Monte Carlo Prediction](https://youtu.be/-YpalutQCKw)
   - [Q learning explained](https://youtu.be/aCEvtRtNO-M)
   - [Solving the basic game of Pong](https://youtu.be/pN7ETkOizGM)
   - [Actor Critic Algorithms](https://youtu.be/w_3mmm0P0j8)
   - [War Robots](https://youtu.be/tm5kQmjfZN8)
    

### Books
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (1st Edition, 1998) [[Book]](http://incompleteideas.net/book/ebook/the-book.html) [[Code]](http://incompleteideas.net/book/code/code.html)
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (2nd Edition, in progress, 2018) [[Book]](http://incompleteideas.net/book/bookdraft2018jan1.pdf) [[Code]](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
 - Csaba Szepesvari, Algorithms for Reinforcement Learning [[Book]](http://www.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
 - David Poole and Alan Mackworth, Artificial Intelligence: Foundations of Computational Agents [[Book Chapter]](http://artint.info/html/ArtInt_262.html)
 - Dimitri P. Bertsekas and John N. Tsitsiklis, Neuro-Dynamic Programming [[Book (Amazon)]](http://www.amazon.com/Neuro-Dynamic-Programming-Optimization-Neural-Computation/dp/1886529108/ref=sr_1_3?s=books&ie=UTF8&qid=1442461075&sr=1-3&refinements=p_27%3AJohn+N.+Tsitsiklis+Dimitri+P.+Bertsekas) [[Summary]](http://www.mit.edu/~dimitrib/NDP_Encycl.pdf)
 - Mykel J. Kochenderfer, Decision Making Under Uncertainty: Theory and Application [[Book (Amazon)]](http://www.amazon.com/Decision-Making-Under-Uncertainty-Application/dp/0262029251/ref=sr_1_1?ie=UTF8&qid=1441126550&sr=8-1&keywords=kochenderfer&pebp=1441126551594&perid=1Y6RG2EGRD26659CJHH9)
 - Deep Reinforcement Learning in Action [[Book(Manning)]](https://www.manning.com/books/deep-reinforcement-learning-in-action)

### Surveys
 - Leslie Pack Kaelbling, Michael L. Littman, Andrew W. Moore, Reinforcement Learning: A Survey, JAIR, 1996. [[Paper]](https://www.jair.org/media/301/live-301-1562-jair.pdf)
 - S. S. Keerthi and B. Ravindran, A Tutorial Survey of Reinforcement Learning, Sadhana, 1994. [[Paper]](http://www.cse.iitm.ac.in/~ravi/papers/keerthi.rl-survey.pdf)
 - Matthew E. Taylor, Peter Stone, Transfer Learning for Reinforcement Learning Domains: A Survey, JMLR, 2009. [[Paper]](http://machinelearning.wustl.edu/mlpapers/paper_files/jmlr10_taylor09a.pdf)
 - Jens Kober, J. Andrew Bagnell, Jan Peters, Reinforcement Learning in Robotics, A Survey, IJRR, 2013. [[Paper]](http://www.ias.tu-darmstadt.de/uploads/Publications/Kober_IJRR_2013.pdf)
 - Michael L. Littman, "Reinforcement learning improves behaviour from evaluative feedback." Nature 521.7553 (2015): 445-451. [[Paper]](http://www.nature.com/nature/journal/v521/n7553/full/nature14540.html)
 - Marc P. Deisenroth, Gerhard Neumann, Jan Peter, A Survey on Policy Search for Robotics, Foundations and Trends in Robotics, 2014. [[Book]](https://spiral.imperial.ac.uk:8443/bitstream/10044/1/12051/7/fnt_corrected_2014-8-22.pdf)
 - Kai Arulkumaran, Marc Peter Deisenroth, Miles Brundage, Anil Anthony Bharath, A Brief Survey of Deep Rei nforcement Learning, IEEE Signal Processing Magazine, 2017. [[Paper]](https://arxiv.org/abs/1708.05866)

### Papers / Thesis
Foundational Papers
 - Marvin Minsky, Steps toward Artificial Intelligence, Proceedings of the IRE, 1961. [[Paper]](http://staffweb.worc.ac.uk/DrC/Courses%202010-11/Comp%203104/Tutor%20Inputs/Session%209%20Prep/Reading%20material/Minsky60steps.pdf) (discusses issues in RL such as the "credit assignment problem")
 - Ian H. Witten, An Adaptive Optimal Controller for Discrete-Time Markov Environments, Information and Control, 1977. [[Paper]](http://www.cs.waikato.ac.nz/~ihw/papers/77-IHW-AdaptiveController.pdf) (earliest publication on temporal-difference (TD) learning rule)
  
Methods
 - Dynamic Programming (DP):
   - Christopher J. C. H. Watkins, Learning from Delayed Rewards, Ph.D. Thesis, Cambridge University, 1989. [[Thesis]](https://www.cs.rhul.ac.uk/home/chrisw/new_thesis.pdf)
 - Monte Carlo:
   - Andrew Barto, Michael Duff, Monte Carlo Inversion and Reinforcement Learning, NIPS, 1994. [[Paper]](http://papers.nips.cc/paper/865-monte-carlo-matrix-inversion-and-reinforcement-learning.pdf)
   - Satinder P. Singh, Richard S. Sutton, Reinforcement Learning with Replacing Eligibility Traces, Machine Learning, 1996. [[Paper]](http://www-all.cs.umass.edu/pubs/1995_96/singh_s_ML96.pdf)
 - Temporal-Difference:
   - Richard S. Sutton, Learning to predict by the methods of temporal differences. Machine Learning 3: 9-44, 1988. [[Paper]](http://webdocs.cs.ualberta.ca/~sutton/papers/sutton-88-with-erratum.pdf)
 - Q-Learning (Off-policy TD algorithm):
   - Chris Watkins, Learning from Delayed Rewards, Cambridge, 1989. [[Thesis]](http://www.cs.rhul.ac.uk/home/chrisw/thesis.html)
 - Sarsa (On-policy TD algorithm):
   - G.A. Rummery, M. Niranjan, On-line Q-learning using connectionist systems, Technical Report, Cambridge Univ., 1994. [[Report]](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=0CDIQFjACahUKEwj2lMm5wZDIAhUHkg0KHa6kAVM&url=ftp%3A%2F%2Fmi.eng.cam.ac.uk%2Fpub%2Freports%2Fauto-pdf%2Frummery_tr166.pdf&usg=AFQjCNHz6IrgcaaO5lzC7t8oEIBY9epozg&sig2=sa-emPme1m5Jav7YmaXsNQ&cad=rja)
   - Richard S. Sutton, Generalization in Reinforcement Learning: Successful examples using sparse coding, NIPS, 1996. [[Paper]](http://webdocs.cs.ualberta.ca/~sutton/papers/sutton-96.pdf)
 - R-Learning (learning of relative values)
   - Andrew Schwartz, A Reinforcement Learning Method for Maximizing Undiscounted Rewards, ICML, 1993. [[Paper-Google Scholar]](https://scholar.google.com/scholar?q=reinforcement+learning+method+for+maximizing+undiscounted+rewards&hl=en&as_sdt=0&as_vis=1&oi=scholart&sa=X&ved=0CBsQgQMwAGoVChMIho6p_MOQyAIVwh0eCh3XWAwM)
 - Function Approximation methods (Least-Square Temporal Difference, Least-Square Policy Iteration)
   - Steven J. Bradtke, Andrew G. Barto, Linear Least-Squares Algorithms for Temporal Difference Learning, Machine Learning, 1996. [[Paper]](http://www-anw.cs.umass.edu/pubs/1995_96/bradtke_b_ML96.pdf)
   - Michail G. Lagoudakis, Ronald Parr, Model-Free Least Squares Policy Iteration, NIPS, 2001. [[Paper]](http://www.cs.duke.edu/research/AI/LSPI/nips01.pdf) [[Code]](http://www.cs.duke.edu/research/AI/LSPI/)
 - Policy Search / Policy Gradient
   - Richard Sutton, David McAllester, Satinder Singh, Yishay Mansour, Policy Gradient Methods for Reinforcement Learning with Function Approximation, NIPS, 1999. [[Paper]](http://papers.nips.cc/paper/1713-policy-gradient-methods-for-reinforcement-learning-with-function-approximation.pdf)
   - Jan Peters, Sethu Vijayakumar, Stefan Schaal, Natural Actor-Critic, ECML, 2005. [[Paper]](https://homes.cs.washington.edu/~todorov/courses/amath579/reading/NaturalActorCritic.pdf)
   - Jens Kober, Jan Peters, Policy Search for Motor Primitives in Robotics, NIPS, 2009. [[Paper]](http://papers.nips.cc/paper/3545-policy-search-for-motor-primitives-in-robotics.pdf)
   - Jan Peters, Katharina Mulling, Yasemin Altun, Relative Entropy Policy Search, AAAI, 2010. [[Paper]](http://www.kyb.tue.mpg.de/fileadmin/user_upload/files/publications/attachments/AAAI-2010-Peters_6439%5b0%5d.pdf)
   - Freek Stulp, Olivier Sigaud, Path Integral Policy Improvement with Covariance Matrix Adaptation, ICML, 2012. [[Paper]](http://arxiv.org/pdf/1206.4621v1.pdf)
   - Nate Kohl, Peter Stone, Policy Gradient Reinforcement Learning for Fast Quadrupedal Locomotion, ICRA, 2004. [[Paper]](http://www.cs.utexas.edu/~pstone/Papers/bib2html-links/icra04.pdf)
   - Marc Deisenroth, Carl Rasmussen, PILCO: A Model-Based and Data-Efficient Approach to Policy Search, ICML, 2011. [[Paper]](http://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf)
   - Scott Kuindersma, Roderic Grupen, Andrew Barto, Learning Dynamic Arm Motions for Postural Recovery, Humanoids, 2011. [[Paper]](http://www-all.cs.umass.edu/pubs/2011/kuindersma_g_b_11.pdf)
   - Konstantinos Chatzilygeroudis, Roberto Rama, Rituraj Kaushik, Dorian Goepp, Vassilis Vassiliades, Jean-Baptiste Mouret, Black-Box Data-efficient Policy Search for Robotics, IROS, 2017. [[Paper](https://arxiv.org/abs/1703.07261)]
 - Hierarchical RL
   - Richard Sutton, Doina Precup, Satinder Singh, Between MDPs and Semi-MDPs: A Framework for Temporal Abstraction in Reinforcement Learning, Artificial Intelligence, 1999. [[Paper]](https://webdocs.cs.ualberta.ca/~sutton/papers/SPS-aij.pdf)
   - George Konidaris, Andrew Barto, Building Portable Options: Skill Transfer in Reinforcement Learning, IJCAI, 2007. [[Paper]](http://www-anw.cs.umass.edu/pubs/2007/konidaris_b_IJCAI07.pdf)
 - Deep Learning + Reinforcement Learning (A sample of recent works on DL+RL)
   - V. Mnih, et. al., Human-level Control through Deep Reinforcement Learning, Nature, 2015. [[Paper]](http://www.readcube.com/articles/10.1038%2Fnature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D)
   - Xiaoxiao Guo, Satinder Singh, Honglak Lee, Richard Lewis, Xiaoshi Wang, Deep Learning for Real-Time Atari Game Play Using Offline Monte-Carlo Tree Search Planning, NIPS, 2014. [[Paper]](http://papers.nips.cc/paper/5421-deep-learning-for-real-time-atari-game-play-using-offline-monte-carlo-tree-search-planning.pdf)
   - Sergey Levine, Chelsea Finn, Trevor Darrel, Pieter Abbeel, End-to-End Training of Deep Visuomotor Policies. ArXiv, 16 Oct 2015. [[ArXiv]](http://arxiv.org/pdf/1504.00702v3.pdf)
   - Tom Schaul, John Quan, Ioannis Antonoglou, David Silver, Prioritized Experience Replay, ArXiv, 18 Nov 2015. [[ArXiv]](http://arxiv.org/pdf/1511.05952v2.pdf)
   - Hado van Hasselt, Arthur Guez, David Silver, Deep Reinforcement Learning with Double Q-Learning, ArXiv, 22 Sep 2015. [[ArXiv]](http://arxiv.org/abs/1509.06461)
   - Volodymyr Mnih, Adrià Puigdomènech Badia, Mehdi Mirza, Alex Graves, Timothy P. Lillicrap, Tim Harley, David Silver, Koray Kavukcuoglu, Asynchronous Methods for Deep Reinforcement Learning, ArXiv, 4 Feb 2016. [[ArXiv]](https://arxiv.org/abs/1602.01783)
    

## Applications
### Game Playing
Traditional Games
  - Backgammon - "TD-Gammon" game play using TD(λ) (Tesauro, ACM 1995) [[Paper]](http://www.bkgm.com/articles/tesauro/tdl.html)
  - Chess - "KnightCap" program using TD(λ) (Baxter, arXiv 1999) [[arXiv]](http://arxiv.org/pdf/cs/9901002v1.pdf)
  - Chess - Giraffe: Using deep reinforcement learning to play chess (Lai, arXiv 2015) [[arXiv]](http://arxiv.org/pdf/1509.01549v2.pdf)

Computer Games
  - Human-level Control through Deep Reinforcement Learning (Mnih, Nature 2015) [[Paper]](http://www.readcube.com/articles/10.1038%2Fnature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D) [[Code]](https://sites.google.com/a/deepmind.com/dqn/) [[Video]](https://www.youtube.com/watch?v=iqXKQf2BOSE)
  - [Flappy Bird Reinforcement Learning](https://github.com/SarvagyaVaish/FlappyBirdRL) [[Video]](https://www.youtube.com/watch?v=xM62SpKAZHU)
  - MarI/O - learning to play Mario with evolutionary reinforcement learning using artificial neural networks (Stanley, Evolutionary Computation 2002) [[Paper]](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf) [[Video]](https://www.youtube.com/watch?v=qv6UVOQ0F44)

### Robotics
  - Policy Gradient Reinforcement Learning for Fast Quadrupedal Locomotion (Kohl, ICRA 2004) [[Paper]](http://www.cs.utexas.edu/~pstone/Papers/bib2html-links/icra04.pdf)
  - Robot Motor SKill Coordination with EM-based Reinforcement Learning (Kormushev, IROS 2010) [[Paper]](http://kormushev.com/papers/Kormushev-IROS2010.pdf) [[Video]](https://www.youtube.com/watch?v=W_gxLKSsSIE)
  - Generalized Model Learning for Reinforcement Learning on a Humanoid Robot (Hester, ICRA 2010) [[Paper]](https://ccc.inaoep.mx/~mdprl/documentos/Hester_2010.pdf) [[Video]](https://www.youtube.com/watch?v=mRpX9DFCdwI&list=PL5nBAYUyJTrM48dViibyi68urttMlUv7e&index=12)
  - Autonomous Skill Acquisition on a Mobile Manipulator (Konidaris, AAAI 2011) [[Paper]](http://lis.csail.mit.edu/pubs/konidaris-aaai11b.pdf) [[Video]](https://www.youtube.com/watch?v=yUICAkSQTZY)
  - PILCO: A Model-Based and Data-Efficient Approach to Policy Search (Deisenroth, ICML 2011) [[Paper]](http://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf)
  - Incremental Semantically Grounded Learning from Demonstration (Niekum, RSS 2013) [[Paper]](http://people.cs.umass.edu/~sniekum/pubs/NiekumRSS2013.pdf)
  - Efficient Reinforcement Learning for Robots using Informative Simulated Priors (Cutler, ICRA 2015) [[Paper]](http://markjcutler.com/papers/Cutler15_ICRA.pdf) [[Video]](https://www.youtube.com/watch?v=kKClFx6l1HY)
  - Robots that can adapt like animals (Cully, Nature 2015) [[Paper](https://arxiv.org/abs/1407.3501)] [[Video](https://www.youtube.com/watch?v=T-c17RKh3uE)] [[Code](https://github.com/resibots/cully_2015_nature)]
  - Black-Box Data-efficient Policy Search for Robotics (Chatzilygeroudis, IROS 2017) [[Paper](https://arxiv.org/abs/1703.07261)] [[Video](https://www.youtube.com/watch?v=kTEyYiIFGPM)] [[Code](https://github.com/resibots/blackdrops)]


### Control
  - An Application of Reinforcement Learning to Aerobatic Helicopter Flight (Abbeel, NIPS 2006) [[Paper]](http://heli.stanford.edu/papers/nips06-aerobatichelicopter.pdf) [[Video]](https://www.youtube.com/watch?v=VCdxqn0fcnE)
  - Autonomous helicopter control using Reinforcement Learning Policy Search Methods (Bagnell, ICRA 2001) [[Paper]](http://repository.cmu.edu/cgi/viewcontent.cgi?article=1082&context=robotics)

### Operations Research
  - Scaling Average-reward Reinforcement Learning for Product Delivery (Proper, AAAI 2004) [[Paper]](http://web.engr.oregonstate.edu/~proper/AAAI04SProper.pdf)
  - Cross Channel Optimized Marketing by Reinforcement Learning (Abe, KDD 2004) [[Paper]](http://www.research.ibm.com/people/n/nabe/kdd04AVAS.pdf)

### Human Computer Interaction
  - Optimizing Dialogue Management with Reinforcement Learning: Experiments with the NJFun System (Singh, JAIR 2002) [[Paper]](http://web.eecs.umich.edu/~baveja/Papers/RLDSjair.pdf)



## Tutorials / Websites
  - Mance Harmon and Stephanie Harmon, [Reinforcement Learning: A Tutorial](http://old.nbu.bg/cogs/events/2000/Readings/Petrov/rltutorial.pdf)
  - C. Igel, M.A. Riedmiller, et al., Reinforcement Learning in a Nutshell, ESANN, 2007. [[Paper]](http://image.diku.dk/igel/paper/RLiaN.pdf)
  - UNSW - [Reinforcement Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/index.html)
    - [Introduction](http://www.cse.unsw.edu.au/~cs9417ml/RL1/introduction.html)
    - [TD-Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/tdlearning.html)
    - [Q-Learning and SARSA](http://www.cse.unsw.edu.au/~cs9417ml/RL1/algorithms.html)
    - [Applet for "Cat and Mouse" Game](http://www.cse.unsw.edu.au/~cs9417ml/RL1/applet.html)
  - [ROS Reinforcement Learning Tutorial](http://wiki.ros.org/reinforcement_learning/Tutorials/Reinforcement%20Learning%20Tutorial)
  - [POMDP for Dummies](http://cs.brown.edu/research/ai/pomdp/tutorial/index.html)
  - Scholarpedia articles on:
    - [Reinforcement Learning](http://www.scholarpedia.org/article/Reinforcement_learning)
    - [Temporal Difference Learning](http://www.scholarpedia.org/article/Temporal_difference_learning)
  - Repository with useful [MATLAB Software, presentations, and demo videos](http://busoniu.net/repository.php)
  - [Bibliography on Reinforcement Learning](http://liinwww.ira.uka.de/bibliography/Neural/reinforcement.learning.html)
  - UC Berkeley - CS 294: Deep Reinforcement Learning, Fall 2015 (John Schulman, Pieter Abbeel) [[Class Website]](http://rll.berkeley.edu/deeprlcourse/)
  - [Blog posts on Reinforcement Learning, Parts 1-4](https://studywolf.wordpress.com/2012/11/25/reinforcement-learning-q-learning-and-exploration/) by Travis DeWolf
  - [The Arcade Learning Environment](http://www.arcadelearningenvironment.org/) - Atari 2600 games environment for developing AI agents
  - [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/) by Andrej Karpathy
  - [Demystifying Deep Reinforcement Learning](https://www.nervanasys.com/demystifying-deep-reinforcement-learning/) 
  - [Let’s make a DQN](https://jaromiru.com/2016/09/27/lets-make-a-dqn-theory/) 
  - [Simple Reinforcement Learning with Tensorflow, Parts 0-8](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0#.78km20i8r) by Arthur Juliani
  - [Practical_RL](https://github.com/yandexdataschool/Practical_RL) - github-based course in reinforcement learning in the wild (lectures, coding labs, projects)
  - [RLenv.directory: Explore and find new reinforcement learning environments.](https://rlenv.directory/)



## Online Demos
 - [Real-world demonstrations of Reinforcement Learning](http://www.dcsc.tudelft.nl/~robotics/media.html)
 - [Deep Q-Learning Demo](http://cs.stanford.edu/people/karpathy/convnetjs/demo/rldemo.html) - A deep Q learning demonstration using ConvNetJS
 - [Deep Q-Learning with Tensor Flow](https://github.com/nivwusquorum/tensorflow-deepq) - A deep Q learning demonstration using Google Tensorflow
 - [Reinforcement Learning Demo](http://cs.stanford.edu/people/karpathy/reinforcejs/) - A reinforcement learning demo using reinforcejs by Andrej Karpathy


## Open Source Reinforcement Learning Platforms
- [OpenAI gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms
- [OpenAI universe](https://github.com/openai/universe) - A software platform for measuring and training an AI's general intelligence across the world's supply of games, websites and other applications
- [DeepMind Lab](https://github.com/deepmind/lab) - A customisable 3D platform for agent-based AI research
- [Project Malmo](https://github.com/Microsoft/malmo) - A platform for Artificial Intelligence experimentation and research built on top of Minecraft by Microsoft
- [ViZDoom](https://github.com/Marqt/ViZDoom) - Doom-based AI research platform for reinforcement learning from raw visual information
- [Retro Learning Environment](https://github.com/nadavbh12/Retro-Learning-Environment) - An AI platform for reinforcement learning based on video game emulators. Currently supports SNES and Sega Genesis. Compatible with OpenAI gym.
- [torch-twrl](https://github.com/twitter/torch-twrl) - A package that enables reinforcement learning in Torch by Twitter
- [UETorch](https://github.com/facebook/UETorch) - A Torch plugin for Unreal Engine 4 by Facebook
- [TorchCraft](https://github.com/TorchCraft/TorchCraft) - Connecting Torch to StarCraft
- [rllab](https://github.com/openai/rllab) - A framework for developing and evaluating reinforcement learning algorithms, fully compatible with OpenAI Gym
- [TensorForce](https://github.com/reinforceio/tensorforce) - Practical deep reinforcement learning on TensorFlow with Gitter support and OpenAI Gym/Universe/DeepMind Lab integration.
- [tf-TRFL](https://github.com/deepmind/trfl/) - A library built on top of TensorFlow that exposes several useful building blocks for implementing Reinforcement Learning agents.
- [OpenAI lab](https://github.com/kengz/openai_lab) - An experimentation system for Reinforcement Learning using OpenAI Gym, Tensorflow, and Keras.
- [keras-rl](https://github.com/matthiasplappert/keras-rl) - State-of-the art deep reinforcement learning algorithms in Keras designed for compatibility with OpenAI.
- [BURLAP](http://burlap.cs.brown.edu) - Brown-UMBC Reinforcement Learning and Planning, a library written in Java
- [MAgent](https://github.com/geek-ai/MAgent) - A Platform for Many-agent Reinforcement Learning. 
- [Ray RLlib](http://ray.readthedocs.io/en/latest/rllib.html) - Ray RLlib is a reinforcement learning library that aims to provide both performance and composability.
- [SLM Lab](https://github.com/kengz/SLM-Lab) - A research framework for Deep Reinforcement Learning using Unity, OpenAI Gym, PyTorch, Tensorflow.
- [Unity ML Agents](https://github.com/Unity-Technologies/ml-agents) - Create reinforcement learning environments using the Unity Editor
- [Intel Coach](https://github.com/NervanaSystems/coach) - Coach is a python reinforcement learning research framework containing implementation of many state-of-the-art algorithms.
