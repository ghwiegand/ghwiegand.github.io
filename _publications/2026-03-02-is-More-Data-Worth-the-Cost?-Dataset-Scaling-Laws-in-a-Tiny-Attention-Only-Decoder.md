---
title: "Is More Data Worth the Cost? Dataset Scaling Laws in a Tiny Attention-Only Decoder"
collection: publications
category: conferences
permalink: /publication/2026-03-02-more-data-worth-cost-scaling-laws-tiny-attention-decoder
excerpt: 'Shows that dataset scaling laws hold even at small scales, where training on only 30% of data achieves about 90% of full performance in a tiny attention-only decoder.'
date: 2026-03-02
venue: 'IEEE SDS 2026 (Full Paper, Zürich) & ICLR 2026 Workshop on Data-FM (Rio de Janeiro, Brazil)'
paperurl: 
citation: 'Wiegand, G.-H., Raichle, L., Staedeli, R., Handschuh, S., Hrycej, T., &amp; Bermeitinger, B. (2026). &quot;Is More Data Worth the Cost? Dataset Scaling Laws in a Tiny Attention-Only Decoder.&quot; <i>IEEE International Conference on Data Science (SDS 2026)</i>, Zürich, Switzerland.'
---

**Accepted as Full Paper at IEEE SDS 2026 (Zürich)**  
**Also presented at ICLR 2026 Workshop on Data-FM**

**Authors:** Götz-Henrik Wiegand, Lorena Raichle, Rico Staedeli, Tomas Hrycej, Bernhard Bermeitinger,  Siegfried Handschuh

**OpenReview:** [NWXflgOD5D](https://openreview.net/forum?id=NWXflgOD5D)  

**Abstract:** Training Transformer language models is expensive, as performance typically improves with increasing dataset size and computational budget. Although scaling laws describe this trend at large scale, their implications in controlled, smaller-scale settings remain less explored. In this work, we isolate dataset-size effects using a strongly reduced attention-only decoder architecture. By training on progressively larger power-of-two subsets, we observe smooth performance improvements accompanied by clear diminishing returns, consistent with scaling-law behavior. Using only about 30% of the training data is sufficient to reach approximately 90% of the full-data validation token-level accuracy. These results provide actionable insights into dataset scaling in a controlled, component-isolated setting and offer practical guidance for balancing dataset size and computational cost in compute-restricted settings, such as small research labs and exploratory model development.