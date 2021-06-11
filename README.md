# Nonlinear_ICA_implementations
A repository of implementations of some nonlinear ICA methods in Pytorch.

Currently implemented:
1. Permutation Contrastive Learning (Hyvärinen A, Morioka H (2017) Nonlinear ICA of temporally dependent stationary sources. Proc 20th Int Conf Artif Intell Stat AISTATS 2017)
2. Identifiable Variational Auto-Encoder (Khemakhem I, Kingma DP, Hyvärinen A (2019) Variational autoencoders and nonlinear ICA: A unifying framework. arXiv 108:)

To implement:
1. Time Contrastive Learning (Hyvarinen A, Morioka H (2016) Unsupervised Feature Extraction by Time-Contrastive Learning and Nonlinear ICA. 1–11)

Comments:
- I am struggling to get both methods to work correctly. 
- TCL version does not scale and cannot recover sources too well as I increase the complexity of the mixing model. 
- iVAE works well for a small latent space but does not do well at larger sizes.
- Fix iVAE for GPU use (minor edit)
