---
title: "PETALE Project"
excerpt: Evaluate business process models without a gold standard, and pinpoint exactly what your modeling method is missing.<br/><img src='/images/petale_pipeline.svg'>"
collection: projects
---

**[View the code on GitHub →](https://https://github.com/LAMA-WeST-Lab/PETALE)**

## Overview

With the automatization of process modeling thanks to Large Language Models (LLMs) technologies, assessing the quality of business process models has become an important stake of business process management. As a given process can be validly captured by more than one model, evaluation remains challenging. Instead of comparing the generated model to a single gold model, our work explore a different approach: comparison to the original process description. We introduce PETALE, a fine-grained evaluation framework that decomposes both process models and their natural-language descriptions into granular semantic components (called tasks), then aligns these components through semantic similarity. In addition to being free from a reference process model, our method provides precise insights of process modeling errors, such as hallucinations and omissions.

<img src='/images/petale_pipeline.svg'>

## Key Features

- TaskPET dataset : 45 annotated process descriptions, along with 35 gold process models (BPMNs made by human experts), and additional process information tasks annotations
- PETALE implementation : end-to-end framework to evaluate process models, giving precise insights on where modeling fails
- Complementary material : in addition to the benchmark in PETALE paper, we conducted supplementary experiments to assess the reliability of our implementation.

## Tech Stack

`Python`
