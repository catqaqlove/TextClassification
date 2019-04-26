# Text Classification
- Dataset: yahoo_answers_csv ([yahoo](https://s3.amazonaws.com/fast-ai-nlp/yahoo_answers_csv.tgz))
- Model: CNN/LSTM/GRU.
- Pytorch: 1.0.1
- Python: 3.6
- torchtext: 0.3.1.
- Support pretrained word embedding.([word2vec](https://github.com/mmihaltz/word2vec-GoogleNews-vectors))

## torchtext
- This package can provide an elegant way to build vocabulary([yahoo](https://torchtext.readthedocs.io/en/latest/index.html#)). 
```
TEXT.build_vocab(dataset, vectors)
```

## Training

- The following command starts training.

```
python main.py
```
