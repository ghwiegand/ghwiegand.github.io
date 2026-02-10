---
title: "A Convexity-Dependent Two-Phase Training Algorithm for Deep Neural Networks"
collection: publications
category: conferences
permalink: /publication/2025-10-22-convexity-dependent-two-phase-training
excerpt: 'Proposes a two-phase optimization algorithm that detects when the loss landscape transitions from non-convex to convex regions, switching from Adam to Conjugate Gradient to substantially improve convergence speed and accuracy.'
date: 2025-10-22
venue: 'Proceedings of the 17th International Joint Conference on Knowledge Discovery, Knowledge Engineering and Knowledge Management (IC3K KDIR 2025)'
paperurl: 'https://arxiv.org/abs/2510.25366'
citation: 'Hrycej, T., Bermeitinger, B., Pavone, M., Wiegand, G.-H., &amp; Handschuh, S. (2025). &quot;A Convexity-Dependent Two-Phase Training Algorithm for Deep Neural Networks.&quot; <i>Proceedings of the 17th International Joint Conference on Knowledge Discovery, Knowledge Engineering and Knowledge Management</i>, 78–86.'
---

**Best Paper Award**

**Authors:** Tomas Hrycej, Bernhard Bermeitinger, Massimo Pavone, Götz-Henrik Wiegand, Siegfried Handschuh

**ORCID:** [0009-0009-0392-056X](https://orcid.org/0009-0009-0392-056X) | **arXiv:** [2510.25366](https://arxiv.org/abs/2510.25366) | **DOI:** [10.5220/0013696100004000](https://doi.org/10.5220/0013696100004000)

**Abstract:** The key task of machine learning is to minimize the loss function that measures the model fit to the training data. The numerical methods to do this efficiently depend on the properties of the loss function. The most decisive among these properties is the convexity or non-convexity of the loss function. The fact that the loss function can have, and frequently has, non-convex regions has led to a widespread commitment to non-convex methods such as Adam. However, a local minimum implies that, in some environment around it, the function is convex. In this environment, second-order minimizing methods such as the Conjugate Gradient (CG) give a guaranteed superlinear convergence. We propose a novel framework grounded in the hypothesis that loss functions in real-world tasks swap from initial non-convexity to convexity towards the optimum. This is a property we leverage to design an innovative two-phase optimization algorithm. The presented algorithm detects the swap point by observing the gradient norm dependence on the loss. In these regions, non-convex (Adam) and convex (CG) algorithms are used, respectively. Computing experiments confirm the hypothesis that this simple convexity structure is frequent enough to be practically exploited to substantially improve convergence and accuracy.
