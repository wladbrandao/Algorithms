[Vers&atilde;o em Portugu&ecirc;s](/README.md)

# Design of Algorithms
This is a set of lectures and material on algorithms design providing an introduction to the main methods and techniques used to implement algorithms for important computational problems. See also the current courses related to this topic:

* [LAD (Laboratory of Algorithms Design](LDA202001M.md): course offered on **mondays** in the 1st semester of 2020 to the students of the [BSc Program in Computer Science](https://www.pucminas.br/unidade/coracao-eucaristico/ensino/graduacao/Paginas/Ciencia-da-Computacao.aspx?tipo=152f25a5-fa8d-4d04-a7ba-57b6b4c21265&campi=ab23480c-5f60-4752-b990-1ac1cf9b8cf5&curso=180#) at [PUC Minas](http://www.pucminas.br).

* [LAD (Laboratory of Algorithms Design](LDA202001W.md): course offered on **wednesdays** in the 1st semester of 2020 to the students of the [BSc Program in Computer Science](https://www.pucminas.br/unidade/coracao-eucaristico/ensino/graduacao/Paginas/Ciencia-da-Computacao.aspx?tipo=152f25a5-fa8d-4d04-a7ba-57b6b4c21265&campi=ab23480c-5f60-4752-b990-1ac1cf9b8cf5&curso=180#) at [PUC Minas](http://www.pucminas.br).

## Introduction
Natural language processing (NLP) is one of the most important technologies since people communicate most everything in language, from emails, instant messages, web search, posts in social networks to customer service and medical reports.
Particularly, NLP refers to the set of methods for making human language accessible to machines \[[2](#Eisenstein-2018-BOOK)\]. It designates the design and analysis of representations, methods and algorithms to solve practical language problems by taking as input or produce as output unstructured natural human language data \[[3](#Goldberg-2017-SLHLT)\]. Usually, problems in NLP involve automatic speech recognition and text summarization, information extraction, machine translation, natural language understanding and generation, sentiment and discouse analysis.

The history of NLP dates back to the 1950s with experiments on automatic machine translation \[[6](#MIT-1952-CMT)\]. In the following years experiments on chatbots, conceptual ontologies and question answering were developed and the proposed approaches were mostly based on complex sets of hand-written rules.
In the late 80's, the introduction of machine learning algorithms for language processing produced a new paradigm distinct from rule-based NLP, with research mostly focusing on the development of statistical models to make probabilistic decisions based on features extracted from text corpus \[[5](#Johnson-2009-EACL)\].

Recent advances in artificial intelligence and high performance computing have led to an intensive use of new machine learning models powering NLP applications.
In particular, deep neural network based approaches have obtained very high performance across many different
NLP tasks \[[4](#Goldberg-2016-JAIR)\]. These models can often be trained with a single end-to-end model and do not require traditional, task specific feature engineering.
Such neural NLP have been they have been more effective for understanding complex language utterances and have been viewed as a new paradigm distinct from statistical NLP.

## Lectures

1. Introduction to NLP [ slides ]
1. Vector representations [ slides ]
1. Language modeling [ slides ]
1. Text classification [ slides ]
1. Linear models for NLP [ slides ]
1. Introduction to neural networks [ slides ]
1. Tagging [ slides ]
1. Sequence labeling [ slides ]
1. Language generation [ slides ]
1. Parsing and context-free grammars [ slides ]
1. Text embeddings [ slides ]
1. Neural language models [ slides ]

## Material

### Videos

1. [Channel: Natural Language Processing with Deep Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) by Stanford University.

### Other Resources

1. [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) by Michael A. Nielsen.
1. [Deep Learning](http://www.deeplearningbook.org) by Ian Goodfellow, Yoshua Bengio and Aaron Courville.

## Further Information

Most of the topics of the lectures are taken from \[[1](#Jurafsky-2019-BOOK)\], \[[2](#Eisenstein-2018-BOOK)\] and \[[3](#Goldberg-2017-SLHLT)\]. Material and assignments are mostly inspired by the Stanford course [Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/).


## References

<a name="Jurafsky-2019-BOOK"></a>\[[1][1]\] Dan Jurafsky, and James H. Martin. Speech and Language Processing. 3rd ed. 2019.

<a name="Eisenstein-2018-BOOK"></a>\[[2][2]\] Jacob Eisenstein. Natural Language Processing. MIT Press. 2018.

<a name="Goldberg-2017-SLHLT"></a>\[[3][3]\] Yoav Goldberg. Neural network methods for natural language processing. Synthesis Lectures on Human Language Technologies, 10(1):1–309. 2017.

<a name="Goldberg-2016-JAIR"></a>\[[4][4]\] Yoav Goldberg. A Primer on Neural Network Models for Natural Language Processing. Journal of Artificial Intelligence Research, 57(1):345-420. 2016.

<a name="Johnson-2009-EACL"></a>\[[5][5]\] Mark Johnson. How the Statistical Revolution Changes (Computational) Linguistics. In Proceedings of the EACL Workshop on the Interaction between Linguistics and Computational Linguistics, p. 3-11, 2009.

<a name="MIT-1952-CMT"></a>\[[6][6]\] Conference on Mechanical Translation. MIT. 1952.

[1]: https://web.stanford.edu/~jurafsky/slp3/
[2]: https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf
[3]: https://doi.org/10.2200/S00762ED1V01Y201703HLT037
[4]: https://doi.org/10.1613/jair.4992
[5]: https://www.aclweb.org/anthology/W09-0103
[6]: http://mt-archive.info/MIT-1952-TOC.htm
