---
title: "QualBench: Benchmarking Chinese LLMs with Localized Professional Qualifications for Vertical Domain Evaluation" 
date: 2025-09-03
tags: ["LLM Application","Benchmark"]
author: ["Mengze Hong","Wailing Ng"]
description: "This paper proposes QualBench, the first benchmark to harness Chinese professional qualification exams, highlighting the importance of localized evaluation in vertical domains." 
summary: "This paper proposes QualBench, the first benchmark to harness Chinese professional qualification exams, highlighting the importance of localized evaluation in vertical domains." 
cover:
    image: "qualbench.png"
    alt: "QualBench: Evaluating LLMs with Localized Chinese Qualifications"
    relative: true
editPost:
    URL: "https://github.com/mengze-hong/QualBench"
    Text: "EMNLP 2025 (Main)"

---
---

##### Abstract

The rapid advancement of Chinese LLMs underscores the need for vertical-domain evaluations to ensure reliable applications. However, existing benchmarks often lack domain coverage and provide limited insights into the Chinese working context. Leveraging qualification exams as a unified framework for expertise evaluation, we introduce QualBench, the first multi-domain Chinese QA benchmark dedicated to localized assessment of Chinese LLMs. The dataset includes over 17,000 questions across six vertical domains, drawn from 24 Chinese qualifications to align with national policies and professional standards. Results reveal an interesting pattern of Chinese LLMs consistently surpassing non-Chinese models, with the Qwen2.5 model outperforming the more advanced GPT-4o, emphasizing the value of localized domain knowledge in meeting qualification requirements. The average accuracy of 53.98% reveals the current gaps in domain coverage within model capabilities. Furthermore, we identify performance degradation caused by LLM crowdsourcing, assess data contamination, and illustrate the effectiveness of prompt engineering and model fine-tuning, suggesting opportunities for future improvements through multi-domain RAG and Federated Learning. 

[[Paper]](qualbench.pdf) [[Code and Data]](https://github.com/mengze-hong/QualBench)

##### Citation

```bibtex
@inproceedings{hong2025qualbench,
    title={QualBench: Benchmarking Chinese {LLM}s with Localized Professional Qualifications for Vertical Domain Evaluation},
    author={Mengze Hong and Wailing Ng and Chen Jason Zhang and Di Jiang},
    booktitle={The 2025 Conference on Empirical Methods in Natural Language Processing},
    year={2025}
}
```