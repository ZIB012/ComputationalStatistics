# Computational_Statistics

### NeuralUQ: A comprehensive library for UQ in neural differential equations and operators
In NeuralUQ, each UQ method is decomposed into a surrogate and an inference method for posterior estimation. NeuralUQ has included various surrogates and inference methods, i.e., 
- Surrogates
  - Bayesian Neural Networks (BNNs)
  - Deterministic Neural Networks, e.g., fully-connected neural networks (FNNs)
  - Deep Generative Models, e.g., Generative Adversarial Nets (GANs)
- Inference Methods
  - Sampling methods
    - Hamiltonian Monte Carlo (HMC)
    - Langevin Dynamics (LD)
    - No-U-Turn (NUTS)
    - Metropolis-adjusted Langevin algorithm (MALA)
  - Variational Methods
    - Mean-field Variational Inference (MFVI)
    - Monte Carlo Dropout (MCD)
  - Ensemble Methods
    - Deep ensembles (DEns)
    - Snapshot ensemble (SEns)
    - Laplace approximation (LA)
    
Users can refer to this paper for the design and description, as well as the examples, of the NeuralUQ library:
- [NeuralUQ: A comprehensive library for uncertainty quantification in neural differential equations and operators](http://arxiv.org/abs/2208.11866)

# Installation
**NeuralUQ** requires the following dependencies to be installed:

- Tensorflow 2.9.1
- TensorFlow Probability 0.17.0

Then install with `python`:

```
$ python setup.py install
```
