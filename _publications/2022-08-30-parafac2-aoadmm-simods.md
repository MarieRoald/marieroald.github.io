---
title: "An AO-ADMM approach to constraining PARAFAC2 on all modes"
collection: publications
permalink: /publication/2022-08-30-parafac2-aoadmm-simods
excerpt: 'Journal paper of the AO-ADMM algorithm for fitting regularized PARAFAC2 models. Also includes some general theory on the PARAFAC2 constraints.'
date: 2022-08-30
venue: 'SIAM Journal on Mathematics of Data Science (SIMODS)'
paperurl: 'https://arxiv.org/abs/2110.01278'
citation: 'Roald M, Schenker C, Calhoun VD, Adali T, Bro R, Cohen JE, Acar E. An AO-ADMM approach to constraining PARAFAC2 on all modes. SIAM Journal on Mathematics of Data Science. 2022;4(3):1191-222.'
---

Analyzing multi-way measurements with variations across one mode of the dataset is a challenge in various fields including data mining, neuroscience and chemometrics. For example, measurements may evolve over time or have unaligned time profiles. The PARAFAC2 model has been successfully used to analyze such data by allowing the underlying factor matrices in one mode (i.e., the evolving mode) to change across slices. The traditional approach to fit a PARAFAC2 model is to use an alternating least squares-based algorithm, which handles the constant cross-product constraint of the PARAFAC2 model by implicitly estimating the evolving factor matrices. This approach makes imposing regularization on these factor matrices challenging. There is currently no algorithm to flexibly impose such regularization with general penalty functions and hard constraints. In order to address this challenge and to avoid the implicit estimation, in this paper, we propose an algorithm for fitting PARAFAC2 based on alternating optimization with the alternating direction method of multipliers (AO-ADMM). With numerical experiments on simulated data, we show that the proposed PARAFAC2 AO-ADMM approach allows for flexible constraints, recovers the underlying patterns accurately, and is computationally efficient compared to the state-of-the-art. We also apply our model to two real-world datasets from neuroscience and chemometrics, and show that constraining the evolving mode improves the interpretability of the extracted patterns.
