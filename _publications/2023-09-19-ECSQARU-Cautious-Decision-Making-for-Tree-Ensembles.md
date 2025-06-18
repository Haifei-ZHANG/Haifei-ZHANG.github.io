---
title: "Cautious decision-making for tree ensembles"
collection: publications
category: conferences
permalink: /publication/2023-09-19-ECSQARU-Cautious-Decision-Making-for-Tree-Ensembles
authors: "<strong>Haifei Zhang</strong>, Benjamin Quost, Marie-Hélène Masson"
date: 2023-09-19
venue: 'European Conference on Symbolic and Quantitative Approaches with Uncertainty (ECSQARU 2023)'
pdfurl: 'http://haifei-zhang.github.io/files/2023-09-19-ECSQARU-Cautious-Decision-Making-for-Tree-Ensembles.pdf'
paperurl: 'https://doi.org/10.1007/978-3-031-45608-4_1'
codeurl: 'https://github.com/Haifei-ZHANG/Cautious-Random-Forest'
---

Cautious classifiers are designed to make indeterminate decisions when the uncertainty on the input data or the model output is too high, so as to reduce the risk of making wrong decisions. In this paper, we propose two cautious decision-making procedures, by aggregating trees providing probability intervals constructed via the imprecise Dirichlet model. The trees are aggregated in the belief functions framework, by maximizing the lower expected discounted utility, so as to achieve a good compromise between model accuracy and determinacy. They can be regarded as generalizations of the two classical aggregation strategies for tree ensembles, i.e., averaging and voting. The efficiency and performance of the proposed procedures are tested on random forests and illustrated on three UCI datasets.