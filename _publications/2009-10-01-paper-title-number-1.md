---
title: "Tackling Federated Unlearning as a Parameter Estimation Problem"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper presents an innovative framework that formulates unlearning as a parameter-estimation problem.'
date: 01-10-2025
venue: 'arXiv prePrint'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://antoniobalordi.github.io/files/paper1.pdf'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Balordi, A. et al. (2025). &quot; Tackling Federated Unlearning as a Parameter Estimation Problem.&quot; <i>arXiv preprint </i>.'
---
Abstract:
Privacy regulations require the erasure of data from deep learning models. This is a significant challenge that is amplified in Federated Learning, where data remains on clients, making full retraining or coordinated updates often infeasible. This work introduces an efficient Federated Unlearning framework based on information theory, modeling leakage as a parameter estimation problem. Our method uses second-order Hessian information to identify and selectively reset only the parameters most sensitive to the data being forgotten. This model-agnostic approach supports categorical and client unlearning without requiring server access to raw client data after the initial information aggregation. Evaluations on benchmark datasets demonstrate strong privacy (MIA success near random, categorical knowledge erased) and high performance (Normalized Accuracy against retrained benchmarks of $$\approx$$ 0.8), while also achieving increased efficiency over complete retraining. Furthermore, in a targeted backdoor attack scenario, our framework effectively neutralizes the malicious trigger, restoring model integrity. This offers a practical solution for data forgetting in FL.
