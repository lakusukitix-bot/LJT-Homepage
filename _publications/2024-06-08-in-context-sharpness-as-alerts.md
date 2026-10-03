---
title: "In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation"
authors:
  - Shiqi Chen
  - Miao Xiong
  - Junteng Liu
  - Zhengxuan Wu
  - Teng Xiao
  - Siyang Gao
  - Junxian He
venue: "Proceedings of the 41st International Conference on Machine Learning (ICML)"
year: 2024
url: "https://arxiv.org/abs/2405.13666"
code: ""
---

**Abstract**: Hallucination remains a critical limitation of large language models, often requiring computationally expensive fine-tuning or alignment procedures. In this work, we propose a lightweight, alignment-free method to detect and mitigate hallucinations using in-context sharpness, a novel metric derived from the internal activation patterns of LLMs. We show that hallucinatory responses consistently exhibit significantly lower sharpness than truthful responses, allowing us to build a binary classifier that can identify hallucinations with high accuracy without any additional training. We further demonstrate that we can prevent hallucinations in real time by adjusting the LLM's sampling parameters based on this sharpness metric. This approach provides a flexible, general-purpose tool for improving LLM reliability across different tasks and domains.

*Third author work conducted during internship at Tencent WXG.*
