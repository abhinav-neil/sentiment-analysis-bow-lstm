# Sentiment Analysis with Neural Models

This repository contains a jupyter notebook which uses various neural models to perform sentence representation and sentiment analysis on the dataset of the Stanford Sentiment Treebank (SST) 

## Models
- Bag-of-words (cbow)
- Continuous bag-of-words (CBOW)
- Deep continuous bag-of-words (Deep CBOW)
- LSTM
- Binary Tree-LSTM
- Child-sum Tree-LSTM

### LSTM variants
- vanilla LSTM
- No input gate (NIG) LSTM
- No output gate (NOG) LSTM
- No forget gate (NFG) LSTM
- No input activation (NIAF) LSTM
- No output activation (NOAF) LSTM
- No peephole (NP) LSTM
- Coupled input and forget (CIFG) LSTM

## Methodology

The models are evaluated based on accuracy. We also evaluate separately on long and short sentences for each model. We also evaluate performance on all subtrees of the original sentence dataset for each model. We use Word2Vec for pretrained embeddings.


## References
- Stanford Sentiment Treebank: [Socher et al., 2013](https://nlp.stanford.edu/sentiment/treebank.html)
- Word2Vec: Word2Vec: [Mikolov et al., 2013](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
- Bag-of-words: [Mikolov et al., 2013](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
- Continuous bag-of-words: [Mikolov et al., 2013](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
- Deep continuous bag-of-words: [Le and Mikolov, 2014](https://cs.stanford.edu/~quocle/paragraph_vector.pdf)
- LSTM: [Hochreiter and Schmidhuber, 1997](http://www.bioinf.jku.at/publications/older/2604.pdf)
- Binary Tree-LSTM: [Tai et al., 2015](https://arxiv.org/pdf/1503.00075.pdf)
- Child-sum Tree-LSTM: [Tai et al., 2015](https://arxiv.org/pdf/1503.00075.pdf)
- LSTM variants: [Gers et al., 2000](https://www.cs.utexas.edu/~gers/papers/lstmforgetbias.pdf)