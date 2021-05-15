---
layout: archive
title: "Reseacrh Highlights"
permalink: /research/
author_profile: true
---

## Machine Learning Enabled High-Resolution DMRSI

Deuterium magnetic resonance spectroscopic imaging (DMRSI) has recently been recognized as a potentially powerful tool for noninvasive imaging of brain energy metabolism and tumor. However, the low sensitivity of DMRSI has significantly limited its utility for both research and clinical applications. This work presents a novel machine learning-based method to address this limitation. The proposed method synergistically integrates physics-based subspace modeling and data-driven deep learning for effective denoising, making high-resolution dynamic DMRSI possible. Specifically, a novel subspace model was used to represent the dynamic DMRSI signals; deep neural networks were trained to capture the low-dimensional manifolds of the spectral and temporal distributions of practical dynamic DMRSI data. The learned subspace and manifold structures were integrated via a regularization formulation to remove measurement noise. Theoretical analysis, computer simulations, and in vivo experiments have been conducted to demonstrate the denoising efficacy of the proposed method which enabled high-resolution imaging capability. The translational potential was demonstrated in tumor-bearing rats, where the Warburg effect associated with cancer metabolism and tumor heterogeneity were successfully captured. The new method may not only provide an effective tool to enhance the sensitivity of DMRSI for basic research and clinical applications but also provide a framework for denoising other spatiospectral data.

![](DMRSI.bmp)

## Improved Estimation of Myelin Water Fractions with Learned Parameter Distributions

Myelin water fraction (MWF) mapping can substantially improve our understanding of several demyelinating diseases. While MWF maps can be obtained from multi-exponential fitting of multi-echo imaging data, current solutions are often very sensitive to noise and modeling errors. Our work first conducted a systematic sensitivity analysis to characterize the conventional exponential models used for MWF estimation. A new estimation method was then proposed for improved estimation of MWF from practical gradient-echo imaging data. The proposed method uses an extended signal model that includes a finite impulse response filter to compensate for practical signal variations. This new model also enables the use of pre-learned parameter distributions as well as low-rank signal structures to improve parameter estimation. The resulting parameter estimation problem was solved optimally in the Bayesian sense. Our sensitivity analysis results showed that the conventional exponential models were very sensitive to measurement noise and modeling errors. Our simulation and experimental results showed that our proposed method provided a substantial improvement in reliability, reproducibility, and robustness of MWF estimates over the conventional methods.  Clinical results obtained from stroke patients indicated that the proposed method, with its improved capability,  could reveal the loss of myelin in lesions, demonstrating its translational potentials.

![](MWF.bmp)
