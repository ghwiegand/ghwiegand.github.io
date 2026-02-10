---
title: "Leveraging Generative AI for Enhancing Domain-Driven Software Design"
collection: publications
category: conferences
permalink: /publication/2024-10-29-leveraging-generative-ai-ddd
excerpt: 'Demonstrates that a 4-bit quantized Code Llama fine-tuned with LoRA on a consumer GPU can generate syntactically correct domain-specific JSON objects for Domain-Driven Design, partially automating metamodel creation.'
date: 2024-10-29
venue: 'Proceedings of the Upper-Rhine Artificial Intelligence Symposium (URAI 2024)'
paperurl: 'https://arxiv.org/abs/2601.20909'
citation: 'Wiegand, G.-H., Stepniak, F., &amp; Baier, P. (2024). &quot;Leveraging Generative AI for Enhancing Domain-Driven Software Design.&quot; <i>Proceedings of the Upper-Rhine Artificial Intelligence Symposium</i>, 2024, 41–50.'
---

**Authors:** Götz-Henrik Wiegand, Filip Stepniak, Patrick Baier

**ORCID:** [0009-0009-0392-056X](https://orcid.org/0009-0009-0392-056X) | **arXiv:** [2601.20909](https://arxiv.org/abs/2601.20909) | **DOI:** [10.60643/URAI.V2024P41](https://doi.org/10.60643/URAI.V2024P41)

**Abstract:** Domain-Driven Design (DDD) is a key framework for developing customer-oriented software, focusing on the precise modeling of an application's domain. Traditionally, metamodels that describe these domains are created manually by system designers, forming the basis for iterative software development. This paper explores the partial automation of metamodel generation using generative AI, particularly for producing domain-specific JSON objects. By training a model on real-world DDD project data, we demonstrate that generative AI can produce syntactically correct JSON objects based on simple prompts, offering significant potential for streamlining the design process. To address resource constraints, the AI model was fine-tuned on a consumer-grade GPU using a 4-bit quantized version of Code Llama and Low-Rank Adaptation (LoRA). Despite limited hardware, the model achieved high performance, generating accurate JSON objects with minimal post-processing. This research illustrates the viability of incorporating generative AI into the DDD process, improving efficiency and reducing resource requirements, while also laying the groundwork for further advancements in AI-driven software development.
