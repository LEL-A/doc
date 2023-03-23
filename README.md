# Documentation of LEL-A (Libre Euro Lingua-Alliance)
The recent results of Alpaca are impressive.
It was shown that it is realistically possible -
even without a supercomputer and a multi-million budget -
to train competitive ChatGPT-style large language models.

On the long run we strive to provide so-called
instruction-following large language models
aka "ChatGPT-style" models for the European language area.

Our goal is to provide models, code, training data and
documentation that is:
1. Free, open-source and permissive (MIT license)
2. Transparent
3. Open for agile contribution and participation
4. State of the art
5. Up-to-date

## Rough Planning
This section plans the first steps and
outlines the individual ventures in the future.

### First Milestone
In the first step we want to train, evaluate and publish
a German and English generative pre-trained transformer
(GPT) model of relatively small size. This model will not
yet have the so-called instruction-following capabilities.

The concrete steps towards this goal are:
1. Provide a clean and appropriate English and German text corpus.
2. Identify training method, training code, model type and hyperparameters.
3. Find a way to get the necessary computation power and storage.
4. Start, monitor and maintain the training.
5. Evaluate the results on reference tasks.
6. Publish the final model and results.

### Second Milestone
- Add instruction-following capabilities by fine-tuning the GPT model from before.
- This could be done in the same style as Alpaca.
An OpenAI API access might be necessary for this, which would add additional costs.
- Identify training method, training code and hyperparameters.
- Find a way to get the necessary computation power and storage.
- Start, monitor and maintain the training.
- Evaluate the results on reference tasks.
- Publish the final model and results.

### Outlook
- add more European languages
- add different programming languages
- use more training data in general
- improve quality of training data
- determine and monitor bias, take countermeasures if necessary
- train larger models
- retrain existing models to keep them current
- update training method, training code, model type and hyperparameters when new research is published

## Impediments and Risks
1. We do not have sufficient computing power. Neither the hardware nor the money to rent.
(see [#5](https://github.com/LEL-A/doc/issues/5))
2. The licensing implications of using the OpenAI API (self-instruct / Alpaca style training) are not entirely clear.
(see [#6](https://github.com/LEL-A/doc/issues/6))
3. The LLaMA training code is not open-sourced.
(see [#4](https://github.com/LEL-A/doc/issues/4))

## Relevant Links
- LLaMA
  - Blog: [Introducing LLaMA: A foundational, 65-billion-parameter large language model](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)
  - arXiv: [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971)
  - [LLaMA Model Card](https://github.com/facebookresearch/llama/blob/main/MODEL_CARD.md)
- GitHub: [ChatLLaMA](https://github.com/juncongmoo/chatllama)
- Alpaca
  - Blog: [Alpaca: A Strong, Replicable Instruction-Following Model](https://crfm.stanford.edu/2023/03/13/alpaca.html)
  - GitHub: [Stanford Alpaca: An Instruction-following LLaMA Model](https://github.com/tatsu-lab/stanford_alpaca)
- Training Data
  - [Common Crawl](https://commoncrawl.org/)
  - [OSCAR](https://oscar-project.github.io/documentation/)
  - [GC4 Corpus](https://german-nlp-group.github.io/projects/gc4-corpus.html)
  - [Online Language Modelling Dataset Pipeline](https://github.com/huggingface/olm-datasets)

## Contribution & Joining our Community
Our commitment to open source means that we are enabling - in fact encouraging - all interested parties 
to contribute and become part of our community. 
Contribution and feedback is encouraged and always welcome.

We communicate via a Slack channel. To get access ...

## Licensing
Copyright (c) 2023 by the LEL-A team

Licensed under the **MIT License** (the "License"); you may not use this file except in compliance with the License.
You may obtain a copy of the License by reviewing the file
[LICENSE](https://raw.githubusercontent.com/LEL-A/doc/main/LICENSE) in the repository.
