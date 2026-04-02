---
title: "Counterfactual Explanations for Cautious Random Forests"
collection: publications
category: manuscripts
permalink: /publication/2026-01-17-ACM-TKDD-Counterfactual-Explanations-for-Cautious-Random-Forests
authors: "<strong>Haifei Zhang</strong>, Benjamin Quost, Marie-Hélène Masson"
date: 2026-01-17
venue: 'ACM Transactions on Knowledge Discovery from Data'
pdfurl: 'http://haifei-zhang.github.io/files/2026-01-17-ACM-TKDD-Counterfactual-Explanations-for-Cautious-Random-Forests.pdf'
paperurl: 'https://dl.acm.org/doi/full/10.1145/3794856'
codeurl: 'https://github.com/Haifei-ZHANG/Explainable-Cautious-Random-Forest'
---

Traditional machine learning models provide a single-class prediction for a given input instance. This may be inadequate in some scenarios, especially when the cost of erroneous predictions is high. Cautious random forests are cautious classification models that may output sets of possible classes as predictions when uncertainty is high, thus reducing the risk of making incorrect decisions. However, making such indeterminate predictions carries a cost, as resolving indeterminacy typically necessitates further analysis and manual intervention. This work focuses on explaining why an indeterminate prediction has been made and how indeterminacy can be resolved. To this end, we use counterfactual examples associated with determinate predictions. We propose a branch-and-bound algorithm that can efficiently generate proximal, plausible, and actionable counterfactual examples. Several experimental results are presented to demonstrate the advantages of our proposed method.