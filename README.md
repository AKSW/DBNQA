# DBNQA
The DBpedia Neural Question Answering (DBNQA) dataset


"DBpedia Neural Question Answering (DBNQA) [Hartmann et al.] is the largest DBpedia-targeting dataset we have found so far and a superset of the Monument dataset. It is also
based on English and SPARQL pairs and contains 894,499 instances in total. In terms
of vocabulary, it has about 131,000 words for English and 244,900 tokens for SPARQL
without any reduction. DBNQA provides a remedy for some drawbacks of the previous two datasets. A large number of generic templates are extracted from the concrete
examples of two existing datasets LC-QUAD and QALD-7-Train [18] by replacing the
entities with placeholders. These templates can subsequently be used in the same approach as the one in the Monument dataset to generate a large dataset." Yin et al., 2019

## Evaluation

An evaluation of different datasets with different translation models provided by Yin et al.

![alt evaluation](https://github.com/AKSW/DBNQA/blob/master/evaluation.png)

## Papers

### Hartman, Marx, and Soru et al., 2018

This paper explains how the dataset was made.

```
@article{hartmann-marx-soru-2018,
  author = {Hartmann, Ann-Kathrin and Marx, Edgard and Soru, Tommaso},
  abstract = {The role of Question Answering is central to the fulfillment of the Semantic Web. Recently, several approaches relying on artificial neural networks have been proposed to tackle the problem of question answering over knowledge graphs. Such techniques are however known to be data-hungry and the creation of training sets requires a substantial manual effort. We thus introduce DBNQA, a comprehensive dataset of 894,499 pairs of questions and SPARQL queries based on templates which are specifically designed on the DBpedia knowledge base. We show how the method used to generate our dataset can be easily reused for other purposes. We report the successful adoption of DBNQA in an experimental phase  and  present  how  it  compares  with  existing  question-answering corpora.},
  booktitle = {Workshop on Linked Data Management, co-located with the W3C WEBBR 2018},
  title = {Generating a Large Dataset for Neural Question Answering over the {DB}pedia Knowledge Base},
  url = {https://www.researchgate.net/publication/324482598_Generating_a_Large_Dataset_for_Neural_Question_Answering_over_the_DBpedia_Knowledge_Base},
  year = 2018
}
```

### Yin et al., 2019

This paper gives an evaluation on DBNQA and other existing datasets for QA using Neural Machine Translation (NMT) approaches.

* arXiv: https://arxiv.org/abs/1906.09302

```
@article{yin2019neural,
  title={Neural Machine Translating from Natural Language to SPARQL},
  author={Yin, Xiaoyu and Gromann, Dagmar and Rudolph, Sebastian},
  journal={arXiv preprint arXiv:1906.09302},
  year={2019}
}
```

## Contact

* Primary contacts: [Edgard Marx](http://emarx.org) and [Tommaso Soru](http://tommaso-soru.it).
* Neural SPARQL Machines [mailing list](https://groups.google.com/forum/#!forum/neural-sparql-machines).
* Follow the [project on ResearchGate](https://www.researchgate.net/project/Neural-SPARQL-Machines).
