# Cognate identification in low-resource languages


## Datasets

Datasets used in the RANLP 2019 paper _"Cross-Family Similarity Learning for Cognate Identification in Low-Resource Languages"_ can be found in the folder `data`:

- `ew_cognates.txt` contains all the cognate pairs used for training the similarity learning models. The words have been obtained from the _Etymological WordNet_ database by [1].

- `sami_vocabs.json` contains the vocabularies for South, North, and Skolt Sami we used as our low-resource test set. The keys are: `sma` - South Sami, `sme` - North Sami, `sms` - Skolt Sami. We obtained these vocabularies from dictionaries compiled by [2].

- `sami_cognates.json` contains those word pairs across the three Sami languages that we know to be cognates, obtained from [3]. The keys in the file stand for language pairs, and the values are tuples containing the cognate words and their indices in the vocabularies.






## References:

1. Gerard de Melo. 2014. Etymological WordNet: Trac- ing the History of Words. In Proceedings of the Ninth International Conference on Language Re- sources and Evaluation (LREC’14), Reykjavik, Ice- land. European Language Resources Association (ELRA).

2. The research group of Sami language technology at the University of Tromssa. http://giellatekno.uit.no/index.eng.html.

3. Álgu, the etymological database for Sami languages. Available at: http://kaino.kotus.fi/algu/.






