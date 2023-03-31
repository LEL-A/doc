# Ideas, Links and Findings

## Multilingual Training
- Efficient Language Model Training through Cross-Lingual and Progressive Transfer Learning
  - [LinkedIn](https://www.linkedin.com/posts/activity-7044989507972030464-g4hC)
  - [arXiv](https://arxiv.org/abs/2301.09626)

## Multimodal Capabilities
- OpenFlamingo:
[Twitter](https://twitter.com/hardmaru/status/1640891630356946944),
[Blog](https://laion.ai/blog/open-flamingo/)

## Data Labeling and Management
- [Argilla](https://www.argilla.io/)
- Good German text embedding model:
[sentence-transformers/paraphrase-multilingual-mpnet-base-v2](https://huggingface.co/sentence-transformers/paraphrase-multilingual-mpnet-base-v2)

## Translation
- [Helsinki-NLP/opus-mt-en-de](https://huggingface.co/Helsinki-NLP/opus-mt-en-de)
- [Fairseq](https://github.com/facebookresearch/fairseq/blob/main/examples/translation/README.md)
```python
en2de = torch.hub.load('pytorch/fairseq', 'transformer.wmt19.en-de',
                       checkpoint_file='model1.pt:model2.pt:model3.pt:model4.pt',
                       tokenizer='moses', bpe='fastbpe')
en2de.eval()  # disable dropout
```

## Other related Organizations and Initiatives
- LAION:
[Website](https://laion.ai/),
[Discord](https://discord.gg/xBPBXfcFHd),
[GitHub](https://github.com/LAION-AI/)
