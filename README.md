# CounterFactual-XAI-Tutorials-and-Papers


CFX (CounterFactual eXplanation) is a popular method for model explanation. It is a post-hoc way that can give actionable explanations to a model result. In this repo, I will list out some SOTA related to CFX.

## Model explanation packages and libraries 
### DiCE [[repo](https://github.com/interpretml/DiCE)]
- Explaining machine learning classifiers through diverse counterfactual explanations [[paper](https://dl.acm.org/doi/abs/10.1145/3351095.3372850)]
### Alibi [[repo](https://github.com/SeldonIO/alibi)]
- Supported methods [[summary](https://github.com/SeldonIO/alibi#model-explanations)]

## Methods for different models
### Model-Agnostic Methods
- DiCE [[example code](https://github.com/interpretml/DiCE/blob/master/docs/source/notebooks/DiCE_model_agnostic_CFs.ipynb)]
  - Randomized sampling
  - KD-Tree (for counterfactuals within the training data)
  - Genetic algorithm 
- CFRL by Seldon Alibi
  - Model-agnostic and Scalable Counterfactual Explanations via Reinforcement Learning [[paper](https://arxiv.org/pdf/2106.02597.pdf)] [[doc](https://docs.seldon.io/projects/alibi/en/latest/methods/CFRL.html)]
### Gradient-Based Methods
- CounterFactual by Seldon Alibi [[doc](https://docs.seldon.io/projects/alibi/en/latest/methods/CF.html)]
  - Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR [[paper](https://arxiv.org/abs/1711.00399)] 
- CEM [[example code](https://docs.seldon.io/projects/alibi/en/stable/methods/CEM.html)]
  - Explanations based on the Missing: Towards Contrastive Explanations with Pertinent Negatives [[paper](https://arxiv.org/abs/1802.07623)] [[source code](https://github.com/IBM/Contrastive-Explanation-Method)] 
- DiCE 
  - An explicit loss-based method [[paper](https://arxiv.org/pdf/1905.07697.pdf)]
  - A Variational AutoEncoder (VAE)-based method [[paper](https://arxiv.org/pdf/1912.03277.pdf)] [[example code](http://interpret.ml/DiCE/notebooks/DiCE_getting_started_feasible.html)]
- GeCo: Quality Counterfactual Explanations in Real Time [[paper](http://vldb.org/pvldb/vol14/p1681-schleich.pdf)] [[source code](https://github.com/mjschleich/GeCo.jl)]
### Model-Specific Methods
- Actionable Recourse in Linear Classification
- Efficient Search for Diverse Coherent Explanations
### CFX on Other Models
- KS Test
  -  Comprehensible Counterfactual Explanation on Kolmogorov-Smirnov Test  [[paper](http://vldb.org/pvldb/vol14/p1583-cong.pdf)] [[source code](https://github.com/research0610/MOCHE)]


## Interdisciplinary Works Towards CFX
- Adquate and Fair Explanations
