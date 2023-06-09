# Guardrail ML

![plot](./static/images/guardrail_img.png)

Guardrail ML is an open-source LLM toolkit for evaluating, benchmarking, and monitoring language models. We will be providing examples with Dolly 2.0, which can be swapped for other HuggingFace models, to democratize fine-tuning, evaluating, and safeguarding LLMs.


## Quickstart 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KCn1HIeD3fQy8ecT74yHa3xgJZvdNvqL?usp=sharing)

Get started with the below tasks in minutes via a free colab instance: 
1. Evaluate LLM outputs/prompts for Text Quality, Toxicity, Bias, Relevance, Sentiment, Prompt Injection, etc.
2. Generate JSON Question & Answer dataset from PDF leveraging LLMs

## Changelog below:

07/12/23 Update:
1. Easily evaluate your LLMs
2. Generate JSON dataset via Dolly (Beta)
3. Quickstart Colab

06/29/23 Update:
1. We are working hard behind the scenes to release a v0.01 version in the coming weeks with accompanying Google Colab notebooks and YouTube video.
2. Upon popular request, we will work towards a tutorial on how to leverage unstructured data for fine-tuning LLMs

06/09/23 Update:
1. Working on releasing developer tools here for evaluating LLMs off HuggingFace for effectiveness, robustness, and custom eval metrics. Stay tuned.

04/14/23 Update:
1. [Fine-tuning Dolly with LoRA 2.0 Colab Notebook](https://colab.research.google.com/drive/1n5U13L0Bzhs32QO_bls5jwuZR62GPSwE?usp=sharing)

04/12/23 Update:
1. [Dolly 2.0 Update Video on YouTube](https://www.youtube.com/watch?v=5sNJpRgZh-s&ab_channel=GenerativeAIEntrepreneurs)
2. [Dolly 2.0 Google Colab (Modified for Colab Free)](https://colab.research.google.com/drive/1A8Prplbjr16hy9eGfWd3-r34FOuccB2c?usp=sharing)
3. [DataBricks Blog post](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)
4. [`databricks-dolly-15k`](https://github.com/databrickslabs/dolly/tree/master/data)

Roadmap - Each with a seperate Colab Notebook Example
- [x] Colab Notebook to Run and Inference Dolly 2.0
- [x] Colab Notebook to Fine-Tune Dolly 2.0 on Alpaca
- [ ] v0.0.01 release of guardrail-ml via $pip install
- [x] Colab Notebook for Quickstart with Guardrail-ML 
- [ ] Evaluating and Benchmarking LLMs example 
- [ ] Evaluation Metrics of LLMs
- [ ] Dataset creation on documents via evolve-instruct
- [ ] Prompt monitoring
- [ ] Redteaming LLMs
