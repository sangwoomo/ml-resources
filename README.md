# Some resources for ML research

Personal and biased selection of ML resources.

**Disclaimer:** I'm a noivce in ML research, and I read only a few of the list.


## Table of Contents
- [Beginner's Guide](#beginners-guide)
- [Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)
- [Reinforcement Learning](#reinforcement-learning)
- [Graphical Model](#graphical-model)
- [Optimization](#optimization)
- [Learning Theory](#learning-theory)
- [Statistics](#statistics)
- [Topics in Machine Learning](#topics-in-machine-learning)
- [Math Backgrounds](#math-backgrounds)
- [Blogs](#blogs)


## Beginner's Guide

**Must Read**
- Machine Learning: A Probabilistic Perspective (Murphy)
- Deep Learning (Goodfellow et al.)
- Reinforcement Learning: An Introduction (Sutton & Barto)

**Recommended**
- Convex Optimization (Boyd & Vandenberghe)
- Graphical Models, Exponential Families, and Variational Inference (Wainwright & Jordan)
- Learning from Data (Abu-Mostafa) *-> for whom interested in learning theory*


## Machine Learning
There are many ML books, but most of them are encyclopedic. <br/>
I recommend to take a course using Murphy or Bishop book.

### Textbook
- Machine Learning: A Probabilistic Perspective (Murphy) :sparkles:
- Pattern Recognition and Machine Learning (Bishop) :sparkles:
- The Elements of Statistical Learning (Hastie et al.)
- Pattern Classification (Duda et al.)
- Bayesian Reasoning and Machine Learning (Barber)

### Lecture
- [Stanford CS229 Machine Learning](http://cs229.stanford.edu) :sparkles:
- [CMU 10701 Mahine Learning](http://www.cs.cmu.edu/~tom/10701_sp11/)
- [Oxford Machine Learning](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)


## Deep Learning
Goodfellow et al. is the new classic. <br/>
For vision and NLP, Stanford lectures would be helpful.

### Textbook
- Deep Learning (Goodfellow et al.) :sparkles:

### Lecture
- [Stanford CS231n Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu) :sparkles:
- [Stanfrod CS224d Deep Learning for Natural Language Processing](http://cs224d.stanford.edu)
- [Oxford Deep Natural Language Processing](https://github.com/oxford-cs-deepnlp-2017/lectures)
- [Stanford Stat385 Theories of Deep Learning](https://stats385.github.io/)

### Tutorial
- [ICML 2017 Sequence-To-Sequence Modeling with Neural Networks](https://sites.google.com/view/seq2seq-icml17)


## Reinforcement Learning
For classic (non-deep) RL, Sutton & Barto is the classic. <br/>
For deep RL, lectures from Berkeley/CMU looks good.

### Textbook
- Reinforcement Learning: An Introduction (Sutton & Barto) :sparkles:
- Algorithms for Reinforcement Learning (Szepesvári)
- Dynamic Programming and Optimal Control (Bertsekas)

### Lecture
- [UCL Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html) :sparkles:
- [Berkeley CS294 Deep Reinforcement Leanring](http://rll.berkeley.edu/deeprlcourse/) :sparkles:
- [CMU 10703 Deep Reinforcement Learing and Control](https://katefvision.github.io/)

### Tutorial
- [ICML 2017 Deep Reinforcement Learning, Decision Making, and Control](https://sites.google.com/view/icml17deeprl)


## Graphical Model
Koller & Friedman is comprehensive, but too encyclopedic. <br/>
I recommend to take an introductory course using Koller & Friedman book. <br/>

Wainwright & Jordan only focuses on variational inference, <br/>
but it gives really good intuition for probabilistic models.

### Textbook
- Probabilistic Graphical Models: Principles and Techniques (Koller & Friedman)
- Graphical Models, Exponential Families, and Variational Inference (Wainwright & Jordan) :sparkles:

### Lecture
- [Stanford CS228 Probabilistic Graphical Models](http://cs.stanford.edu/~ermon/cs228/index.html)
- [CMU 10708 Probabilistic Graphical Models](http://www.cs.cmu.edu/~epxing/Class/10708/) :sparkles:


## Optimization
Boyd & Vandenberghe is the classic, but I think it's too boring. <br/>
Reading chapter 2-5 would be enough.

Bertsekas more concentrates on convex analysis. <br/>
Nocedal & Wright more concentrates on optimization.

### Textbook
- Convex Optimization (Boyd & Vandenberghe) :sparkles:
- Convex Optimization Theory (Bertsekas)
- Numerical Optimization (Nocedal & Wright)

### Lecture
- [Stanford EE364a Convex Optimization I](http://stanford.edu/class/ee364a/) :sparkles:
- [Stanford EE364b Convex Optimization II](http://stanford.edu/class/ee364a/)
- [MIT 6.253 Convex Analysis and Optimization](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-253-convex-analysis-and-optimization-spring-2012/index.htm)

### Tutorial
- [ICML 2017 Recent Advances in Stochastic Convex and Non-Convex Optimization](http://people.csail.mit.edu/zeyuan/topics/icml-2017)


## Learning Theory
In my understanding, there are two major topics in learning theory:

- **Learning Theory:** VC-dimension, PAC-learning
- **Online Learning:** regret bound, multi-armed bandit

For learning theory, Kearns & Vazirani is the classic; but it's too old-fashined. <br/>
Abu-Mostafa is a good introductory book, and I think it's enough for most people.

For online learning, Cesa-Bianchi & Lugosi is the classic. <br/>
For multi-armed bandit, Bubeck & Cesa-Bianchi provides a good survey.

### Textbook (Learning Theory)
- Learning from Data (Abu-Mostafa) :sparkles:
- Foundations of Machine Learning (Mohri et al.)
- An Introduction to Computational Learning Theory (Kearns & Vazirani) 

### Textbook (Online Learning)
- Prediction, Learning, and Games (Cesa-Bianchi & Lugosi)
- Regret Analysis of Stochastic and Nonstochastic Multi-armed Bandit Problems (Bubeck & Cesa-Bianchi)

### Lecture
- [Caltech Learning from Data](https://work.caltech.edu/telecourse.html) :sparkles:
- [CMU 15859 Machine Learning Theory](http://www.cs.cmu.edu/~avrim/ML14/)
- [Berkeley CS281b/Stat241b Statistical Learning Theory](https://www.stat.berkeley.edu/~bartlett/courses/2014spring-cs281bstat241b/)
- [MIT 9.520 Statistical Learning Theory and Applications](http://www.mit.edu/~9.520/fall15/)

### Tutorial
- [ICML 2017 Real World Interactive Learning](http://hunch.net/~rwil/)


## Statistics
Statistics is a broad area; hence, I listed only a few of them. <br/>
For advanced topics, lectures from Berkeley/Stanford/CMU/MIT looks really cool. <br/>

### Textbook (Statistical Inference)
- All of Statistics (Wasserman)
- Computer Age Statistical Inference (Efron & Hastie) :sparkles:
- Time Series Analysis and Its Applications: With R Examples (Shumway & Stoffer)

### Textbook (Nonparametrics)
- All of Nonparametric Statistics (Wasserman)
- Introduction to Nonparametric Estimation (Tsybakov)
- Gaussian Process and Machine Learning (Rasmussen & Williams) :sparkles:
- Bayesian Nonparametrics (Ghosh & Ramamoorthi) :sparkles:

### Textbook (Advanced Topics)
- High-Dimensional Statistics: A Non-Asymptotic Viewpoint (Wainwright) :sparkles:
- Statistics for High-Dimensional Data (Bühlmann & van de Geer)
- Asymptotic Statistics (van der Vaart)
- Empirical Processes in M-Estimation (van der Vaart)

### Lecture
- [Berkeley Stat210a Theoretical Statistics I](https://www.stat.berkeley.edu/~wfithian/courses/stat210a/)
- [Berkeley Stat210b Theoretical Statistics II](https://people.eecs.berkeley.edu/~jordan/courses/210B-spring17/)
- [Stanford Stat300a Theory of Statistics](https://web.stanford.edu/~lmackey/stats300a/)
- [Stanford CS369m Algorithms for Massive Data Set Analysis](http://cs.stanford.edu/people/mmahoney/cs369m/)
- [CMU 36755 Advanced Statistical Theory I](http://www.stat.cmu.edu/~arinaldo/36755/F16/)
- [MIT 18.S997 High-Dimensional Statistics](https://ocw.mit.edu/courses/mathematics/18-s997-high-dimensional-statistics-spring-2015/)


## Topics in Machine Learning
Miscellaneous topics related to machine learning. <br/>
There are much more subfields, but I'll not list them all.

### Information Theory
- Elements of Information Theory (Cover & Thomas)
- Information Theory, Inference, and Learning Algorithms (MacKay)

### Network Science
- Networks, Crowds, and Markets: Reasoning about a Highly Connected World (Easley & Kleinberg)
- Social and Economic Networks (Jackson)

### Markov Chain
- Markov Chains (Norris)
- Markov Chains and Mixing Times (Levin et al.)

### Game Theory
- Algorithmic Game Theory (Nisan et al.)
- Multiagent Systems: Algorithmic, Game-Theoretic, and Logical Foundations (Shoham & Leyton-Brown)

### Combinatorics
- The Probabilistic Method (Alon & Spencer)
- A First Course in Combinatorial Optimization (Lee)

### Algorithm
- Introduction to Algorithms (Cormen et al.)
- Randomized Algorithms (Motwani & Raghavan)
- Approximation Algorithms (Vazirani)

### Geometric View
- Topological Data Analysis (Wasserman)
- Methods of Information Geometry (Amari & Nagaoka)
- Algebraic Geometry and Statistical Learning Theory (Watanabe)

### Some Lectures
- [MIT 18.409 Algorithmic Aspects of Machine Learning](http://people.csail.mit.edu/moitra/409.html)
- [MIT 18.409 An Algorithmist's Toolkit](http://stellar.mit.edu/S/course/18/fa09/18.409/)

### Tutorial
- [ICML 2017 Interpretable Machine Learning](http://people.csail.mit.edu/beenkim/icml_tutorial.html)
- [ICML 2017 Robustness Meets Algorithms (and Vice-Versa)](http://people.csail.mit.edu/moitra/robusttutorial.html)


## Math Backgrounds
I selected essential topics for machine learning. <br/>
Personally, I think more analysis / matrix / geometry never hurts.

### Probability
- Probability: Theory and Examples (Durrett)
- Theoretical Statistics (Keener)
- Stochastic Processes (Bass)
- Probability and Statistics Cookbook (Vallentin)

### Linear Algebra
- Linear Algebra (Hoffman & Kunze)
- Matrix Analysis (Horn & Johnson)
- Matrix Computations (Golub & Van Loan)
- The Matrix Cookbook (Petersen & Pedersen)

### Large Deviations
- Concentration Inequalities and Martingale Inequalities (Chung & Lu)
- An Introduction to Matrix Concentration Inequalities (Tropp)


## Blogs
**TBD**
Acknowledge to https://stats385.github.io/blogs.

### Research Group
- DeepMind Blog
- OpenAI Blog
- FAIR Blog
- BAIR Blog
- Distill
- Cambridge MLG

## Persoanal Blog
- Andrej Karpathy
- Colah
- inFERENCe
