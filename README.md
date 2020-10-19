# Neural-Machine-Translation
Seq-2-Seq modelling for language translation.

## Description:
Building Seq-2-Seq model using Encoder-Decoder architecture with Attention mechanism for translating Italian language to English language.

## Attention Ref: https://arxiv.org/pdf/1508.04025.pdf

### Dataset: http://www.manythings.org/anki/ (Italian - English)

## Results:
| model | Avg.BLEU score |
| ------| ---------------| 
|Simple Encoder-Decoder |0.6605|
|Encoder-Decoder (Attention -Concat) |0.7623|
|Encoder-Decoder (Attention -General) |0.7678|

## Contains one file:
Seq_2_Seq.ipynb - Data preparation and translation.
