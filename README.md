# WikiBias as an Extrapolation Corpus for Bias Detection
Code and data for EMNLP2024 paper

This paper explores whether it is possible to train a machine learning model using Wikipedia data to detect subjectivity in sentences and generalize effectively to other domains.


Unzip the data.zip and lexicon.zip files before running the notebooks. 

## Cite as
```
@inproceedings{salas-jimenez-etal-2024-wikibias,
    title = "{W}iki{B}ias as an Extrapolation Corpus for Bias Detection",
    author = "Salas-Jimenez, K.  and
      Lopez-Ponce, Francisco Fernando  and
      Ojeda-Trueba, Sergio-Luis  and
      Bel-Enguix, Gemma",
    editor = "Lucie-Aim{\'e}e, Lucie  and
      Fan, Angela  and
      Gwadabe, Tajuddeen  and
      Johnson, Isaac  and
      Petroni, Fabio  and
      van Strien, Daniel",
    booktitle = "Proceedings of the First Workshop on Advancing Natural Language Processing for Wikipedia",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.wikinlp-1.10",
    pages = "46--52",
    abstract = "This paper explores whether it is possible to train a machine learning model using Wikipedia data to detect subjectivity in sentences and generalize effectively to other domains. To achieve this, we performed experiments with the WikiBias corpus, the BABE corpus, and the CheckThat! Dataset. Various classical models for ML were tested, including Logistic Regression, SVC, and SVR, including characteristics such as Sentence Transformers similarity, probabilistic sentiment measures, and biased lexicons. Pre-trained models like DistilRoBERTa, as well as large language models like Gemma and GPT-4, were also tested for the same classification task.",
}
```