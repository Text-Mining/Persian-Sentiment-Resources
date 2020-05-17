# Awesome Persian Sentiment Analysis Resources
[FarsiYar Text-Mining Group](https://text-mining.ir) try to collect best resources for opinion mining in the Persian language.


Please participate in its development.

## Deep Neural Networks in Persian Sentiment Analysis
- [2020-DeepSentiPers: Deep Learning Models Plus Data Augmentation Methods in Persian Sentiment Analysis](https://arxiv.org/abs/2004.05328) ([codes](https://github.com/JoyeBright/DeepSentiPers), [talk](https://www.researchgate.net/publication/338570412_A_Deep_Persian_Sentiment_Analysis_Framework))

## Sentiment Analysis Challenges
- [2019-Sentiment Analysis Challenges in Persian Language](https://arxiv.org/abs/1907.04407)
- [2018-The Impact of Sentiment Features on the Sentiment Polarity Classification in Persian Reviews](https://profdoc.um.ac.ir/articles/a/1064471.pdf)

## Sentiment Lexicon
- ["PersianSWN"](../master/PersianSWN.csv) : (2017) [HesNegar: Persian Sentiment WordNet](http://jsdp.rcisp.ac.ir/article-1-554-fa.pdf)
- ["PerSent"](../master/PerSent.xlsx) : (2016) [PerSent: A Freely Available Persian Sentiment Lexicon](https://link.springer.com/chapter/10.1007/978-3-319-49685-6_28)
- ["LexiPers V1.0"](../master/LexiPersV1.0.zip) : (2015) [LexiPers: An ontology based sentiment lexicon for Persian](https://www.researchgate.net/profile/Pedram_Hosseini2/publication/317057113_LexiPers_An_ontology_based_sentiment_lexicon_for_Persian/links/59235cf3458515e3d409c04e/LexiPers-An-ontology-based-sentiment-lexicon-for-Persian.pdf)
- ["Lexicon-based Sentiment Analysis Data"](../master/Lexicon-based%20Sentiment%20Analysis.zip) : (2015) [Lexicon-based Sentiment Analysis for Persian Text](https://pdfs.semanticscholar.org/5375/aafd8b4ac9c1dc4c7f5f3119304f38c1c785.pdf)
- ["UTIIS Sentiment GoldData"](../master/UTIIS-Sentiment-golddata.zip) : (2014) [Semi-supervised word polarity identification in resource-lean languages](https://www.sciencedirect.com/science/article/pii/S0893608014001269)

## Sentiment Tagged Corpus (dataset)
- ["SentiPers V1.0"](../master/SentiPersV1.0.rar) : (2018) [SentiPers: a sentiment analysis corpus for Persian](https://arxiv.org/ftp/arxiv/papers/1801/1801.07737.pdf)
- ["SentiFars"](../master/Labeled-Sentences.xlsx) : (2019) [SentiFars: A Persian Polarity Lexicon for Sentiment Analysis](https://www.researchgate.net/publication/335877038_SentiFars_A_Persian_Polarity_Lexicon_for_Sentiment_Analysis)

## HesNegar: Persian Sentiment WordNet 
You can download csv version of this resource from : ["PersianSWN.csv"](../master/PersianSWN.csv).


Each line (entry) has 5 fields :
1. Synset id (based on Princeton WordNet standard format): ```IdNumber-PosTag``` e.g. 00001740-a
2. Persian word.
3. Confidence value (based on [FerdowsNet](http://jsdp.rcisp.ac.ir/article-1-554-fa.pdf) WordNet).
4. Positivity value.
5. Negativity value. 


**Sample data:**
```
00001740-a	توانا	1.00	0.125	0.000
00051373-a	توانا	0.45	0.375	0.250
00001740-a	قادر	0.24	0.125	0.000
00002098-a	عاجز	1.00	0.000	0.750
00051696-a	عاجز	0.18	0.000	0.500
00002098-a	ناتوان	0.75	0.000	0.750
00051696-a	ناتوان	0.58	0.000	0.500
```


> For more information, please visit [our paper in the Signal and Data Processing Journal](http://jsdp.rcisp.ac.ir/article-1-554-en.html "HesNegar: Persian Sentiment WordNet")

---

> [سرویس تحلیل متن (متن کاوی) فارسی‌یار](https://text-mining.ir "مجموعه ابزارهای پردازش متن برای زبان فارسی")
