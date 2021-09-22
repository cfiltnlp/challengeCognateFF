# Cognate Detection Repository

## Details

This repository contains the data for two publications:

1. Challenge Dataset of Cognates and False Friend Pairs from Indian Languages (LREC 2020)

2. Harnessing Cross-lingual Features to Improve Cognate Detection for Low-resource Languages (COLING 2020)


## Dataset
We release the dataset described in our LREC submission with this repository. Please find the datasets D1, D2, and D3 as described in the paper here in their respective folders.

From here, D1 and D2 can be combined to replicate our COLING 2020 experiments on Cognate Detection for Indian Languages. The ILCI Parallel corpus used for Machine Translation-based experiments described in the paper is not distributable and licenced by TDIL, Indian Government. 
Kindly request the parallel corpus data from TDIL to replicated these experiments.

D3 is only concerning the LREC 2020 paper as it is the data which contains False Friends for Indian Languages

## Citing
Please use the following citation while citing the LREC 2020 work:

```latex
@inproceedings{kanojia-etal-2020-challenge,
    title = "Challenge Dataset of Cognates and False Friend Pairs from {I}ndian Languages",
    author = "Kanojia, Diptesh  and
      Kulkarni, Malhar  and
      Bhattacharyya, Pushpak  and
      Haffari, Gholamreza",
    booktitle = "Proceedings of the 12th Language Resources and Evaluation Conference",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2020.lrec-1.378",
    pages = "3096--3102",
    abstract = "Cognates are present in multiple variants of the same text across different languages (e.g., {``}hund{''} in German and {``}hound{''} in the English language mean {``}dog{''}). They pose a challenge to various Natural Language Processing (NLP) applications such as Machine Translation, Cross-lingual Sense Disambiguation, Computational Phylogenetics, and Information Retrieval. A possible solution to address this challenge is to identify cognates across language pairs. In this paper, we describe the creation of two cognate datasets for twelve Indian languages namely Sanskrit, Hindi, Assamese, Oriya, Kannada, Gujarati, Tamil, Telugu, Punjabi, Bengali, Marathi, and Malayalam. We digitize the cognate data from an Indian language cognate dictionary and utilize linked Indian language Wordnets to generate cognate sets. Additionally, we use the Wordnet data to create a False Friends{'} dataset for eleven language pairs. We also evaluate the efficacy of our dataset using previously available baseline cognate detection approaches. We also perform a manual evaluation with the help of lexicographers and release the curated gold-standard dataset with this paper.",
    language = "English",
    ISBN = "979-10-95546-34-4",
}
```

Please use the following citation while citing the COLING 2020 work:

```latex
@inproceedings{kanojia-etal-2020-harnessing,
    title = "Harnessing Cross-lingual Features to Improve Cognate Detection for Low-resource Languages",
    author = "Kanojia, Diptesh  and
      Dabre, Raj  and
      Dewangan, Shubham  and
      Bhattacharyya, Pushpak  and
      Haffari, Gholamreza  and
      Kulkarni, Malhar",
    booktitle = "Proceedings of the 28th International Conference on Computational Linguistics",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2020.coling-main.119",
    doi = "10.18653/v1/2020.coling-main.119",
    pages = "1384--1395",
    abstract = "Cognates are variants of the same lexical form across different languages; for example {``}fonema{''} in Spanish and {``}phoneme{''} in English are cognates, both of which mean {``}a unit of sound{''}. The task of automatic detection of cognates among any two languages can help downstream NLP tasks such as Cross-lingual Information Retrieval, Computational Phylogenetics, and Machine Translation. In this paper, we demonstrate the use of cross-lingual word embeddings for detecting cognates among fourteen Indian Languages. Our approach introduces the use of context from a knowledge graph to generate improved feature representations for cognate detection. We, then, evaluate the impact of our cognate detection mechanism on neural machine translation (NMT), as a downstream task. We evaluate our methods to detect cognates on a challenging dataset of twelve Indian languages, namely, Sanskrit, Hindi, Assamese, Oriya, Kannada, Gujarati, Tamil, Telugu, Punjabi, Bengali, Marathi, and Malayalam. Additionally, we create evaluation datasets for two more Indian languages, Konkani and Nepali. We observe an improvement of up to 18{\%} points, in terms of F-score, for cognate detection. Furthermore, we observe that cognates extracted using our method help improve NMT quality by up to 2.76 BLEU. We also release our code, newly constructed datasets and cross-lingual models publicly.",
}
```






