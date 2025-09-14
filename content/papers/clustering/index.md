---
title: "Dial-In LLM: Human-Aligned LLM-in-the-loop Intent Clustering for Customer Service Dialogues" 
date: 2025-09-03
tags: ["LLM Application","LLM-in-the-loop"]
author: ["Mengze Hong","Wailing Ng"]
description: "This paper introduces the largest Chinese intent clustering dataset and proposes an LLM-in-the-loop intent clustering framework, which seamlessly integrates the semantic understanding capabilities of LLMs with conventional text clustering algorithms." 
summary: "This paper introduces the largest Chinese intent clustering dataset and proposes an LLM-in-the-loop intent clustering framework, which seamlessly integrates the semantic understanding capabilities of LLMs with conventional text clustering algorithms." 
cover:
    image: "clustering.png"
    alt: "Dial-In LLM: Human-Aligned LLM-in-the-loop Intent Clustering"
    relative: true
editPost:
    URL: "https://arxiv.org/abs/2412.09049"
    Text: "EMNLP 2025 (Main)"

---
---

##### Abstract

Discovering customer intentions is crucial for automated service agents, yet existing intent clustering methods often fall short due to their reliance on embedding distance metrics and neglect of underlying semantic structures. To address these limitations, we propose an LLM-in-the-loop (LLM-ITL) intent clustering framework, integrating the language understanding capabilities of LLMs into conventional clustering algorithms. Specifically, this paper (1) examines the effectiveness of fine-tuned LLMs in semantic coherence evaluation and intent cluster naming, achieving over 95% accuracy aligned with human judgments; (2) designs an LLM-ITL framework that facilitates the iterative discovery of coherent intent clusters and the optimal number of clusters; and (3) introduces context-aware techniques tailored for customer service dialogue. Since existing English benchmarks lack sufficient semantic diversity and intent coverage, we further present a comprehensive Chinese dialogue intent dataset comprising over 100k real customer service calls with 1,507 human-annotated clusters. The proposed approaches significantly outperform LLM-guided baselines, achieving notable improvements in clustering quality, cost efficiency, and downstream applications. Combined with several best practices, our findings highlight the prominence of LLM-in-the-loop techniques for scalable dialogue data mining. [[Paper]](dial-in-llm.pdf) [[Code and Data]](https://github.com/mengze-hong/Dial-in-LLM)

---

##### Citation

```bibtex
@inproceedings{hong2025dialin,
    title={Dial-In {LLM}: Human-Aligned {LLM}-in-the-loop Intent Clustering for Customer Service Dialogues},
    author={Mengze Hong and Wailing Ng and Chen Jason Zhang and Yuanfeng SONG and Di Jiang},
    booktitle={The 2025 Conference on Empirical Methods in Natural Language Processing},
    year={2025}
}
```