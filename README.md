# PyZLabelLDA
An extension of original ZLabelLDA code.http://pages.cs.wisc.edu/~andrzeje/research/zl_lda.html

# Overview

This software implements an extension of LDA [2] which allows the use of "topic-in-set knowledge", or z-labels [1]. This allows the user to supply (possibly noisy) labels or set-labels for specific latent topic z-values. The inference method is Collapsed Gibbs sampling [3]. This code can also be used to do "standard" LDA, similar to [3] (see example code). 

The model is implemented as a Python C extension module.

# Reference

[1] Latent Dirichlet Allocation with Topic-in-Set Knowledge 
Andrzejewski, D. and Zhu, X. 
NAACL 2009 Workshop on Semi-supervised Learning for NLP (NAACL-SSLNLP 2009) 
(pdf)

[2] Latent Dirichlet Allocation 
Blei, D. M., Ng, A. Y., and Jordan, M. I. 
Journal of Machine Learning Research (JMLR), 3, Mar. 2003, 993-1022.

[3] Finding Scientific Topics 
Griffiths, T., and Steyvers, M. 
Proceedings of the National Academy of Sciences (PNAS), 101, 5228-5235.
