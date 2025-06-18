---
title: "Cautious weighted random forests"
collection: publications
category: manuscripts
permalink: /publication/2023-03-01-ESWA-Cautious-weighted-random-forests
authors: "Haifei Zhang, Benjamin Quost, Marie-Hélène Masson"
date: 2023-03-01
venue: 'Expert Systems with Applications'
pdfurl: 'http://haifei-zhang.github.io/files/2023-03-01-ESWA-Cautious-weighted-random-forests.pdf'
paperurl: 'https://doi.org/10.1016/j.eswa.2022.118883'
codeurl: 'https://github.com/Haifei-ZHANG/Cautious-Random-Forest'
---

Random forest is an efficient and accurate classification model, which makes decisions by aggregating a set of trees, either by voting or by averaging class posterior probability estimates. However, tree outputs may be unreliable in presence of scarce data. The imprecise Dirichlet model (IDM) provides workaround, by replacing point probability estimates with interval-valued ones. This paper investigates a new tree aggregation method based on the theory of belief functions to combine such probability intervals, resulting in a cautious random forest classifier. In particular, we propose a strategy for computing tree weights based on the minimization of a convex cost function, which takes both determinacy and accuracy into account and makes it possible to adjust the level of cautiousness of the model. The proposed model is evaluated on 25 UCI datasets and is demonstrated to be more adaptive to the noise in training data and to achieve a better compromise between informativeness and cautiousness.