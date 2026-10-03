---
title: "Composing Parameter-Efficient Modules with Arithmetic Operations"
authors:
  - Jinghan Zhang
  - Shiqi Chen
  - Junteng Liu
  - Junxian He
venue: "Advances in Neural Information Processing Systems (NeurIPS)"
year: 2023
url: "https://arxiv.org/abs/2310.02252"
code: "https://github.com/SJTU-LIT/Composing-PEMs"
---

**Abstract**: Parameter-Efficient Fine-Tuning (PEFT) methods, such as LoRA, have become standard for adapting large pre-trained language models to downstream tasks while maintaining a small number of trainable parameters. However, existing PEFT methods are limited to a fixed set of pre-defined modules and cannot be dynamically composed in novel ways. In this work, we propose a new framework for composing parameter-efficient modules using arithmetic operations (addition, multiplication, subtraction, etc.) on the weight matrices of pre-trained models. This approach allows us to create custom PEFT modules that are optimized for specific tasks without requiring additional training. We demonstrate that our method outperforms existing PEFT approaches across a range of NLP tasks, including text classification, question answering, and named entity recognition.

*Work conducted at Shanghai Jiao Tong University.*
