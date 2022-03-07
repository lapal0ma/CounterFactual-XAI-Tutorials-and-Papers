# CounterFactual-XAI-Tutorials-and-Papers


CFX (CounterFactual eXplanation) is a popular method for model explanation. It is a post-hoc way that can give actionable explanations to a model result. In this repo, I will list out some SOTA related to CFX.
##### Notes: latest work are marked with fire 🔥

## 📖 Model explanation packages and libraries 
### DiCE [[repo](https://github.com/interpretml/DiCE)]
- Explaining machine learning classifiers through diverse counterfactual explanations [[paper](https://dl.acm.org/doi/abs/10.1145/3351095.3372850)]
### Alibi [[repo](https://github.com/SeldonIO/alibi)]
- Supported methods [[summary](https://github.com/SeldonIO/alibi#model-explanations)]

## 📚 Survey paper
- (arthur.ai) Counterfactual Explanations for Machine Learning: A Review [[paper](https://arxiv.org/pdf/2010.10596.pdf)]
  - Evaluation of Counterfactual Generation Algorithms [[Google Sheet](https://docs.google.com/spreadsheets/d/15V7NOZQh4LQMkglLHtPvgcEQf_yaGNCfQHwG1zOFCz4/edit#gid=0)]

## 💡 Methods and works for different models
### Model-Agnostic Methods
- DiCE [[example code](https://github.com/interpretml/DiCE/blob/master/docs/source/notebooks/DiCE_model_agnostic_CFs.ipynb)]
  - Randomized sampling
  - KD-Tree (for counterfactuals within the training data)
  - Genetic algorithm 
- CFRL by Seldon Alibi [[example code](https://docs.seldon.io/projects/alibi/en/latest/examples/cfrl_adult.html)] [[doc](https://docs.seldon.io/projects/alibi/en/latest/methods/CFRL.html)]
  - 🔥 Model-agnostic and Scalable Counterfactual Explanations via Reinforcement Learning [[paper](https://arxiv.org/pdf/2106.02597.pdf)]
#### Liz's Reading list (so far)
- (Nips 2021) Designing Counterfactual Generators using Deep Model Inversion [[paper](https://proceedings.neurips.cc/paper/2021/file/8ca01ea920679a0fe3728441494041b9-Paper.pdf)]
  - No need training data 
- (Nips 2021) Towards Robust and Reliable Algorithmic Recourse [[paper](https://proceedings.neurips.cc/paper/2021/file/8ccfb1140664a5fa63177fb6e07352f0-Paper.pdf)]
  - Data shifting
  - Adversarial training 
- (KDD 2021) Model-Based Counterfactual Synthesizer for Interpretation [[paper](https://arxiv.org/abs/2106.08971)]
- CounteRGAN: Generating Realistic Counterfactuals with Residual Generative Adversarial Nets [[paper](https://arxiv.org/abs/2009.05199)]
- (ICLR 2021) Counterfactual generative networks [[paper](https://arxiv.org/pdf/2101.06046.pdf)][[source code](https://github.com/autonomousvision/counterfactual_generative_networks)]
- (AAAI 2022) Amortized Generation of Sequential Algorithmic Recourses for Black-box Models[[paper](https://arxiv.org/pdf/2106.03962.pdf)] 
  -  Algorithmic Recourses (AR) and sequential ARs
  -  Reinforcement learning
- (AAAI 2022) Diverse, Global and Amortised Counterfactual Explanations for Uncertainty Estimates [[paper](https://arxiv.org/abs/2112.02646)]

### Gradient-Based Methods
- CounterFactual (by Seldon Alibi) [[example code](https://docs.seldon.io/projects/alibi/en/latest/examples/cf_mnist.html)] [[doc](https://docs.seldon.io/projects/alibi/en/latest/methods/CF.html)]
  - Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR [[paper](https://arxiv.org/abs/1711.00399)] 
- CEM (By Seldon Alibi) [[example code](https://docs.seldon.io/projects/alibi/en/latest/examples/cem_iris.html)] [[doc](https://docs.seldon.io/projects/alibi/en/stable/methods/CEM.html)]
  - Explanations based on the Missing: Towards Contrastive Explanations with Pertinent Negatives [[paper](https://arxiv.org/abs/1802.07623)] [[source code](https://github.com/IBM/Contrastive-Explanation-Method)] 
- DiCE 
  - An explicit loss-based method [[paper](https://arxiv.org/pdf/1905.07697.pdf)]
  - A Variational AutoEncoder (VAE)-based method [[paper](https://arxiv.org/pdf/1912.03277.pdf)] [[example code](http://interpret.ml/DiCE/notebooks/DiCE_getting_started_feasible.html)]
- 🔥 GeCo: Quality Counterfactual Explanations in Real Time [[paper](http://vldb.org/pvldb/vol14/p1681-schleich.pdf)] [[source code](https://github.com/mjschleich/GeCo.jl)]
### Model-Specific Methods
- Actionable Recourse in Linear Classification [[paper](https://arxiv.org/pdf/1809.06514.pdf)] [[source code](https://github.com/ustunb/actionable-recourse)]
- Efficient Search for Diverse Coherent Explanations [[paper](https://arxiv.org/pdf/1901.04909.pdf)] [[source code](https://bitbucket.org/ChrisRussell/diverse-coherent-explanations/src/master)]
### CFX on Others
- KS Test
  -  🔥 Comprehensible Counterfactual Explanation on Kolmogorov-Smirnov Test  [[paper](http://vldb.org/pvldb/vol14/p1583-cong.pdf)] [[source code](https://github.com/research0610/MOCHE)]

## 📺 Tutorials and PPT
- Post-hoc counterfactual generation with supervised autoencoder [[ppt](https://project.inria.fr/aimlai/files/2021/09/XAI_ECML-final.pdf)]
- If Only We Had Better Counterfactual Explanations: Five Key Deficits to Rectify in the Evaluation of Counterfactual XAI Techniques [[paper](https://arxiv.org/pdf/2103.01035.pdf)]
## 👩‍🏫 Interdisciplinary Works Towards CFX
- Adquate and Fair Explanations [[paper](https://arxiv.org/abs/2001.07578)]
