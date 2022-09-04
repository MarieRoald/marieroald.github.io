---
title: "PARAFAC2 AO-ADMM: constraints in all modes"
collection: publications
permalink: /publication/2021-08-23-parafac2-aoadmm-eusipco
excerpt: 'Initial publication of the AO-ADMM algorithm for fitting regularized PARAFAC2 models.'
date: 2021-08-23
venue: 'EUSIPCO&apos;21'
paperurl: 'https://arxiv.org/abs/2102.02087'
citation: 'Roald M, Schenker C, Cohen JE, Acar E. PARAFAC2 AO-ADMM: constraints in all modes. 2021 29th European Signal Processing Conference (EUSIPCO) 2021 Aug 23 (pp. 1040-1044). EURASIP.'
---

The PARAFAC2 model provides a flexible alternative to the popular CANDECOMP/PARAFAC (CP) model for tensor decompositions. Unlike CP, PARAFAC2 allows factor matrices in one mode (i.e., evolving mode) to change across tensor slices, which has proven useful for applications in different domains such as chemometrics, and neuroscience. However, the evolving mode of the PARAFAC2 model is traditionally modelled implicitly, which makes it challenging to regularise it. Currently, the only way to apply regularisation on that mode is with a flexible coupling approach, which finds the solution through regularised least-squares subproblems. In this work, we instead propose an alternating direction method of multipliers (ADMM)-based algorithm for fitting PARAFAC2 and widen the possible regularisation penalties to any proximable function. Our numerical experiments demonstrate that the proposed ADMM-based approach for PARAFAC2 can accurately recover the underlying components from simulated data while being both computationally efficient and flexible in terms of imposing constraints. 