# DEVDAN
DEVDAN: Deep Evolving Denoising Autoencoder. Neurocomputing 2019.

# Abstract
The Denoising Autoencoder (DAE) enhances the flexibility of data stream method in exploiting unlabeled samples. Nonetheless, the feasibility of DAE for data stream analytic deserves in-depth study because it characterizes a fixed network capacity which cannot adapt to rapidly changing environments. Deep evolving denoising autoencoder (DEVDAN), is proposed in this paper. It features an open structure in the generative phase and the discriminative phase where the hidden units can be automatically added and discarded on the fly. The genera-tive phase refines the predictive performance of discriminative model exploiting unlabeled data. Furthermore, DEVDAN is free of the problem-specific threshold and works fully in the single-pass learning fashion. We show that DEVDAN can find competitive network architecture compared with state-of-the-art methods on the classification task using ten prominent datasets simulated under the prequential test-then-train protocol.

# Citation
If you use this code, please cite:

@article{DEVDAN,
  author    = {Mahardhika Pratama and
               Andri Ashfahani and
               Edwin Lughofer and
               Yew{-}Soon Ong},
  title     = {DEVDAN: Deep Evolving Denoising Autoencoder},
  journal   = {Neurocomputing},
  year      = {2019}
}
