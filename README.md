# Welcome to SYNLP!

The followings are some of our representative research papers.

**Notes**: The **_Language_** collumn in the following tables indicates that the models are evaluated on those languages in the paper. It does not mean the model will not work on other languages.

## Word Embedding and Pre-trained LM

|Name|Paper|Code|Language|
|----|----|----|----|
|DSG|[Directional Skip-Gram: Explicitly Distinguishing Left and Right Context for Word Embeddings](https://aclanthology.org/N18-2028/)|[link](https://ai.tencent.com/ailab/nlp/en/embedding.html)|Chinese|
|ZEN 1.0|[ZEN: Pre-training Chinese Text Encoder Enhanced by N-gram Representations](https://aclanthology.org/2020.findings-emnlp.425/)|[link](https://github.com/sinovation/ZEN)|Chinese|
|ZEN 2.0|[ZEN 2.0: Continue Training and Adaption for N-gram Enhanced Text Encoders](https://arxiv.org/abs/2105.01279)|[link](https://github.com/sinovation/ZEN2)|Arabic, Chinese|
|T-DNA|[Taming Pre-trained Language Models with N-gram Representations for Low-Resource Domain Adaptation](https://aclanthology.org/2021.acl-long.259/)|[link](https://github.com/shizhediao/t-dna)|English|

**Model Recommendation**: [DSG](https://ai.tencent.com/ailab/nlp/en/embedding.html) provides 200-dimensional word embeddings for around 8M Chinese words.
[ZEN 2.0](https://github.com/sinovation/ZEN2) provides large pre-trained language models (the large version uses 24 layers of self-attentions with 1024 dimensional hidden vectors) for Arabic and Chinese. The models are trained on large corpus and enhance text modeling through n-grams.

## Chinese Word Segmentation and POS Tagging

|Name|Paper|Code|Language|
|----|----|----|----|
|WMSeg|[Improving Chinese Word Segmentation with Wordhood Memory Networks](https://www.aclweb.org/anthology/2020.acl-main.734/)|[link](https://github.com/synlp/WMSeg)|Chinese|
|TwASP|[Joint Chinese Word Segmentation and Part-of-speech Tagging via Two-way Attentions of Auto-analyzed Knowledge](https://aclanthology.org/2020.acl-main.735/)|[link](https://github.com/synlp/TwASP)|Chinese|
|McASP|[Joint Chinese Word Segmentation and Part-of-speech Tagging via Multi-channel Attention of Character N-grams](https://aclanthology.org/2020.coling-main.187/)|[link](https://github.com/synlp/McASP)|Chinese|
|GCASeg|[Federated Chinese Word Segmentation with Global Character Associations](https://aclanthology.org/2021.findings-acl.376/)|[link](https://github.com/synlp/GCASeg)|Chinese|

**Model Recommendation**: [WMSeg](https://github.com/synlp/WMSeg) and [McASP](https://github.com/synlp/McASP) contains easy-to-use CWS and joint CWS and POS tagging models that are based on BERT and ZEN. Models trained on different datasets are available for downloading.

## Parsing

|Name|Paper|Code|Language|
|----|----|----|----|
|SAPar|[Improving Constituency Parsing with Span Attention](https://aclanthology.org/2020.findings-emnlp.153/)|[link](https://github.com/synlp/SAPar)|Arabic, Chinese, English|
|DMPar|[Enhancing Structure-aware Encoder with Extremely Limited Data for Graph-based Dependency Parsing](https://aclanthology.org/2022.coling-1.483/)|[link](https://github.com/synlp/DMPar)|English|
|NeST-CCG|[Supertagging Combinatory Categorial Grammar with Attentive Graph Convolutional Networks](https://aclanthology.org/2020.emnlp-main.487/)|[link](https://github.com/synlp/NeST-CCG)|English|

**Model Recommendation**: [SAPar](https://github.com/synlp/SAPar) provides constituent parsers (which are based on BERT, XLNet, and ZEN) for Arabic, Chinese, and English;
[DMPar](https://github.com/synlp/DMPar) provides code for dependency parsing;
[NeST-CCG](https://github.com/synlp/NeST-CCG) offers BERT-based models for English CCG supertagging. Both repositories provide pre-trained models and they are easy-to-use.

## Semantic Role Labeling

|Name|Paper|Code|Language|
|----|----|----|----|
|SRL-MM|[Syntax-driven Approach for Semantic Role Labeling](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.772.pdf)|[link](https://github.com/synlp/SRL-MM)|English|


## Named Entity Recognition

|Name|Paper|Code|Language|
|----|----|----|----|
|SANER|[Named Entity Recognition for Social Media Texts with Semantic Augmentation](https://aclanthology.org/2020.emnlp-main.107/)|[link](https://github.com/synlp/SANER)|Chinese,English|
|AESINER|[Improving Named Entity Recognition with Attentive Ensemble of Syntactic Information](https://aclanthology.org/2020.findings-emnlp.378/)|[link](https://github.com/cuhksz-nlp/AESINER)|Chinese,English|
|BioKMNER|[Improving biomedical named entity recognition with syntactic information](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03834-6)|[link](https://github.com/synlp/BioKMNER)|English|

**Model Recommendation**: [SANER](https://github.com/cuhksz-nlp/SANER) use pre-trained language models and word embeddings in text modeling, with the semantic of similar words are used to enhance text understanding. Pre-trained models are available for downloading and they are easy-to-use.

## Coreference Resolution

|Name|Paper|Code|Language|
|----|----|----|----|
|Pronoun-Coref-KG|[Knowledge-aware Pronoun Coreference Resolution](https://aclanthology.org/P19-1083/)|[link](https://github.com/HKUST-KnowComp/Pronoun-Coref-KG)|English|
|Pronoun-Coref|[Incorporating Context and External Knowledge for Pronoun Coreference Resolution](https://aclanthology.org/N19-1093/)|[link](https://github.com/HKUST-KnowComp/Pronoun-Coref)|English|
|Visual_PCR|[What You See is What You Get: Visual Pronoun Coreference Resolution in Dialogues](https://aclanthology.org/D19-1516/)|[link](https://github.com/HKUST-KnowComp/Visual_PCR)|English|

**Model Recommendation**: [Pronoun-Coref](https://github.com/HKUST-KnowComp/Pronoun-Coref) uses GloVe and ELMo embeddings in text modeling. The model is light and easy-to-use.

## Aspect-level Sentiment Analysis

|Name|Paper|Code|Language|
|----|----|----|----|
|ASA-TGCN|[Aspect-based Sentiment Analysis with Type-aware Graph Convolutional Networks and Layer Ensemble](https://aclanthology.org/2021.naacl-main.231/)|[link](https://github.com/synlp/ASA-TGCN)|English|
|ASA-WD|[Enhancing Aspect-level Sentiment Analysis with Word Dependencies](https://aclanthology.org/2021.eacl-main.326/)|[link](https://github.com/synlp/ASA-WD)|English|
|ASA-CLD|[Complementary Learning of Aspect Terms for Aspect-based Sentiment Analysis](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.760.pdf)|[link]()|English|
|DGSA|[Joint Aspect Extraction and Sentiment Analysis with Directional Graph Convolutional Networks](https://aclanthology.org/2020.coling-main.24/)|[link](https://github.com/synlp/DGSA)|English|
|ASA-TM|[Improving Federated Learning for Aspect-based Sentiment Analysis via Topic Memories](https://aclanthology.org/2021.emnlp-main.321/)|[link](https://github.com/synlp/ASA-TM)|English|

**Model Recommendation**: [DGSA](https://github.com/synlp/DGSA) provides an end-to-end solution (the model are based on BERT) for aspect-level sentiment analysis, which can be directly used to process raw text.

## Relation Extraction

|Name|Paper|Code|Language|
|----|----|----|----|
|RE-AGCN|[Dependency-driven Relation Extraction with Attentive Graph Convolutional Networks](https://aclanthology.org/2021.acl-long.344/)|[link](https://github.com/synlp/RE-AGCN)|English|
|RE-TAMM|[Relation Extraction with Type-aware Map Memories of Word Dependencies](https://aclanthology.org/2021.findings-acl.221/)|[link](https://github.com/synlp/RE-TaMM)|English|
|RE-DMP|[Improving Relation Extraction through Syntax-induced Pre-training with Dependency Masking](https://aclanthology.org/2022.findings-acl.147/)|[link](https://github.com/synlp/RE-DMP)|English|
|RE-NGCN|[Relation Extraction with Word Graphs from N-grams](https://aclanthology.org/2021.emnlp-main.228/)|[link](https://github.com/cuhksz-nlp/RE-NGCN)|English|
|RE-AMT|[Enhancing Relation Extraction via Adversarial Multi-task Learning](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.666.pdf)|[link](https://github.com/synlp/RE-AMT)|English|

**Model Recommendation**: [RE-AGCN](https://github.com/synlp/RE-AGCN) provides BERT-based models for relation extraction, where the model leverages the auto-parsed dependency tree of the input text to have a better understanding to the text.

## Domain Adaptation

|Name|Paper|Code|Language|
|----|----|----|----|
|T-DNA|[Taming Pre-trained Language Models with N-gram Representations for Low-Resource Domain Adaptation](https://aclanthology.org/2021.acl-long.259/)|[link](https://github.com/shizhediao/t-dna)|English|
|SDG4DA|[Reinforced Training Data Selection for Domain Adaptation](https://aclanthology.org/P19-1189/)|[link](https://github.com/timerstime/SDG4DA)|English|
|DPM4DA|[Domain Adaptation for Disease Phrase Matching with Adversarial Networks](https://aclanthology.org/W18-2315/)|--|English|
|TD4DA|[Entropy-based Training Data Selection for Domain Adaptation](https://aclanthology.org/C12-2116/)|--|Chinese, English|
|GM4DA|[Using a goodness measurement for domain adaptation: A case study on Chinese word segmentation](https://aclanthology.org/L12-1580/)|--|Chinese|

**Model Recommendation**: [T-DNA](https://github.com/shizhediao/t-dna) is a Transformer-based language model for domain adaptation, which can be used easily.

## Medical NER

|Name|Paper|Code|Language|
|----|----|----|----|
|HET-MC|[Summarizing Medical Conversations via Identifying Important Utterances](https://www.aclweb.org/anthology/2020.coling-main.63/)|[link](https://github.com/synlp/HET-MC)|Chinese|
|BioKMNER|[Improving biomedical named entity recognition with syntactic information](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03834-6)|[link](https://github.com/synlp/BioKMNER)|English|

## Language Resource

|Name|Paper|Code|Language|
|----|----|----|----|
|ChiMed|[ChiMed: A Chinese Medical Corpus for Question Answering](https://aclanthology.org/W19-5027/)|[link](https://github.com/yuanheTian/ChiMed)|Chinese|
|ChiMST|[ChiMST: A Chinese Medical Corpus for Word Segmentation and Medical Term Recognition](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.607.pdf)|[link](https://github.com/synlp/ChiMST)|Chinese|
|Chinese CCGBank|[Chinese CCGBank Construction from Tsinghua Chinese Treebank](https://www.jstor.org/stable/26455289?seq=12#metadata_info_tab_contents)|--|Chinese|
|HNZ|[The Construction of a Segmented and Part-of-speech Tagged Archaic Chinese Corpus: A Case Study on Huainanzi](http://faculty.washington.edu/fxia/mpapers/2013/lau2013-cnccl.pdf)|[link](http://uakari.ling.washington.edu/corpus/hnz/)|Chinese|
