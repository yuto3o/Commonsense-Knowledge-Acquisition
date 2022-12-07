<!-- omit in toc -->
# Commonsense Knowledge Acquisition

<!-- omit in toc -->
## TOC
- [1. Keynotes & Workshops](#1-keynotes--workshops)
- [2. Population](#2-population)
- [3. CSK Base](#3-commonsense-knowledge-base)
- [4. CSK Mining](#4-commonsense-knowledge-mining)
- [5. PTM as CSKB](#5-pretrained-language-model-as-commonsense-knowledge-base)
- [6. Neural CSK Reasoning](#6-neural-commonsense-knowledge-reasoning)

<!-- omit in toc -->
## Scholars

- mpi-inf [[homepage]](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research)
  > Commonsense knowledge about object properties, human behavior and general concepts is crucial for robust AI applications. However, automatic acquisition of this knowledge is challenging because of sparseness and bias in online sources.

- AllenAI
  - Niket Tandon [[github]](https://github.com/nikett)
  - Yejin Choi [[homepage]](https://homes.cs.washington.edu/~yejin/)

- usc-isi-i2 [[homepage]](https://usc-isi-i2.github.io/home/)
  > ISI's Center on Knowledge Graphs research group combines artificial intelligence, the semantic web, and database integration techniques to solve complex information integration problems. We leverage general research techniques across information-intensive disciplines, including medical informatics, geospatial data integration and the social Web.

- Yangqiu Song [[homepage]](https://www.cse.ust.hk/~yqsong/)

---


## 1. Keynotes & Workshops
- COIN: COmmonsense INference in Natural Language Processing.  EMNLP-IJCNLP. 2019. [[link]](https://coinnlp.github.io/)
- Fact Extraction and Verification. EMNLP / FEVER. 2020. [[link]](https://fever.ai/index.html)
- Commonsense Reasoning for Natural Language Processing. ACL. 2020. [[link]](https://homes.cs.washington.edu/~msap/acl2020-commonsense/)
- Common Sense Knowledge Graphs. AAAI. 2020. [[link]](https://usc-isi-i2.github.io/AAAI21workshop/)
- MH2: Commonsense Knowledge Acquisition and Representation. AAAI. 2021. [[link]](https://usc-isi-i2.github.io/AAAI21Tutorial/)
- Commonsense AI: Myth and Truth. ICLR. 2021. [[link]](https://iclr.cc/virtual/2021/invited-talk/3719)
- Information to Wisdom: Commonsense Knowledge Extraction and Compilation. WSDM. 2021. [[link]](https://www.mpi-inf.mpg.de/commonsense-tutorial-wsdm-2021)
- Commonsense Knowledge Acquisition and Reasoning. CCKS: T4. 2021. [[link]](http://sigkg.cn/ccks2021/?page_id=23) [[video]](https://hub.baai.ac.cn/view/11404)


## 2. Population
- **[DICE]** Joint Reasoning for Multi-Faceted Commonsense Knowledge. AKBC. 2020. [[paper]](https://www.akbc.ws/2020/papers/QnPV72SZVt)
- Commonsense Knowledge in Wikidata. Workshop on wikidata at ISWC. 2020. [[paper]](https://arxiv.org/abs/2008.08114)
- CogNet: Bridging Linguistic Knowledge, World Knowledge and Commonsense Knowledge. AAAI. 2021. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/18029)
- Lawyers are Dishonest? Quantifying Representational Harms in Commonsense Knowledge Resources. EMNLP. 2021. [[paper]](https://aclanthology.org/2021.emnlp-main.410/)
- NegatER: Unsupervised Discovery of Negatives in Commonsense Knowledge Bases. EMNLP. 2021. [[paper]](https://aclanthology.org/2021.emnlp-main.456/)
- CSKG: The CommonSense Knowledge Graph. ESWC. 2021. [[paper]](https://arxiv.org/abs/2012.11490)
- Dimensions of Commonsense Knowledge. KBS. 2021. [[paper]](https://arxiv.org/abs/2101.04640)
- UnCommonSense: Informative Negative Knowledge about Everyday Concepts. CIKM 2022. [[paper]](https://doi.org/10.1145/3511808.3557484) 
- Do Children Texts Hold The Key To Commonsense Knowledge?. EMNLP. 2022. [[paper]](https://arxiv.org/pdf/2210.04530)


## 3. Commonsense Knowledge Base
- WordNet: An Electronic Lexical Database. The MIT Press. 1998. [[paper]](https://doi.org/10.7551/mitpress/7287.001.0001)
- The Berkeley FrameNet Project. COLING-ACL. 1998. [[paper]](https://aclanthology.org/P98-1013/)
- HowNet - a hybrid language and knowledge resource. NLP-KE. 2003. [[paper]](https://ieeexplore.ieee.org/document/1276017)
  - OpenHowNet: An Open Sememe-based Lexical Knowledge Base. ArXiv. 2019. [[paper]](https://arxiv.org/abs/1901.09957)
- Probase: a probabilistic taxonomy for text understanding. SIGMOD. 2012. [[paper]](https://doi.org/10.1145/2213836.2213891)
  - Probase+: Inferring Missing Links in Conceptual Taxonomies. TKDE. 2017. [[paper]](https://doi.org/10.1109/TKDE.2017.2653115)
  - CCN-Probase: A Data-Driven Approach for Large-Scale Chinese Taxonomy Construction. ICDE. 2019. [[paper]](https://doi.org/10.1109/ICDE.2019.00178)
- ConceptNet 5: A Large Semantic Network for Relational Knowledge. The People's Web Meets NLP. 2013. [[paper]](https://doi.org/10.1007/978-3-642-35085-6_6)
  - ConceptNet 5.5: An Open Multilingual Graph of General Knowledge. AAAI. 2017. [[paper]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14972)
- CN-DBpedia: A Never-Ending Chinese Knowledge Extraction System. IEA/AIE. 2017. [[paper]](https://link.springer.com/chapter/10.1007%2F978-3-319-60045-1_44)
  - CN-DBpedia2: An Extraction and Verification Framework for Enriching Chinese Encyclopedia Knowledge Base. Data Intell. 2019. [[paper]](https://doi.org/10.1162/dint_a_00017)
- ATOMIC: An Atlas of Machine Commonsense for If-Then Reasoning. AAAI. 2019. [[paper]](https://doi.org/10.1609/aaai.v33i01.33013027)
- C3KG: A Chinese Commonsense Conversation Knowledge Graph. ACL Findings. 2022. [[paper]](https://doi.org/10.48550/arXiv.2204.02549)


## 4. Commonsense Knowledge Mining
- WebChild: Harvesting and Organizing Commonsense Knowledge from the Web. WSDM. 2014. [[paper]](https://dl.acm.org/doi/10.1145/2556195.2556245)
  - Smarter Than You Think: Acquiring Comparative Commonsense from the Web. AAAI. 2014. [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8649)
  - Lights, Camera, Action: Knowledge Extraction from Movie Scripts. AAAI. 2015. [[paper]](https://dl.acm.org/doi/10.1145/2740908.2742756)
  - Knowlywood: Mining Activity Knowledge From Hollywood Narratives. CIKM. 2015. [[paper]](https://dl.acm.org/doi/10.1145/2806416.2806583)
  - Commonsense in Parts: Mining Part-Whole Relations from the Web and Image Tags. AAAI. 2016. [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12337)
  - WebChild 2.0: Fine-Grained Commonsense Knowledge Distillation. ACL. 2017. [[paper]](https://www.aclweb.org/anthology/P17-4020/)
- Automatic Extraction of Commonsense LocatedNear Knowledge. ACL. 2018. [[paper]](https://aclanthology.org/P18-2016/)
- **[Quasimodo]** Commonsense Properties from Query Logs and Question Answering Forums. CIKM. 2019. [[paper]](https://dl.acm.org/doi/10.1145/3357384.3357955)
  - Inside Quasimodo: Exploring Construction and Usage of Commonsense Knowledge. CIKM. 2020 [[paper]](https://dl.acm.org/doi/10.1145/3340531.3417416)
- **[VoCSK]** Mining Verb-Oriented Commonsense Knowledge. ICDE. 2020. [[paper]](https://ieeexplore.ieee.org/document/9101187/)
  - VoCSK: Verb-oriented commonsense knowledge mining with taxonomy-guided induction. AIJ. 2022. [[paper]](https://doi.org/10.1016/j.artint.2022.103744)
- CapableOf Reasoning: A Step Towards Commonsense Oracle. SIGIR. 2020. [[paper]](https://dl.acm.org/doi/10.1145/3397271.3401251)
- **[ASER]** ASER: A Large-scale Eventuality Knowledge Graph. WWW. 2020. [[paper]](https://dl.acm.org/doi/10.1145/3366423.3380107)
  - TransOMCS: From Linguistic Graphs to Commonsense Knowledge. IJCAI. 2020. [[paper]](https://doi.org/10.24963/ijcai.2020/554)
  - DISCOS: Bridging the Gap between Discourse Knowledge and Commonsense Knowledge. WWW. 2021. [[paper]](https://doi.org/10.1145/3442381.3450117)
  - Acquiring and Modelling Abstract Commonsense Knowledge via Conceptualization. Arxiv. 2022. [[paper]](https://arxiv.org/abs/2206.01532)
  - ASER: Towards large-scale commonsense knowledge acquisition via higher-order selectional preference over eventualities. AIJ. 2022. [[paper]](https://doi.org/10.1016/j.artint.2022.103740)
- AliCoCo2: Commonsense Knowledge Extraction, Representation and Application in E-commerce. KDD. 2021. [[paper]](https://doi.org/10.1145/3447548.3467203)
- **[Ascent]** Advanced Semantics for Commonsense Knowledge Extraction. WWW. 2021. [[paper]](https://arxiv.org/abs/2011.00905)
  - Inside ASCENT: Exploring a Deep Commonsense Knowledge Base and its Usage in Question Answering. ACL. 2021. [[paper]](https://aclanthology.org/2021.acl-demo.5/)
  - **[Ascent++]** Refined Commonsense Knowledge from Large-Scale Web Contents. TKDE. 2022. [[paper]](https://www.doi.org/10.1109/tkde.2022.3206505)
- Alleviating the Knowledge-Language Inconsistency: A Study for Deep Commonsense Knowledge. TASLP. 2022. [[paper]](https://doi.org/10.1109/TASLP.2021.3138721)


## 5. Pretrained Language Model as Commonsense Knowledge Base
- Commonsense Knowledge Mining from Pretrained Models. EMNLP-IJCNLP. 2019. [[paper]](https://aclanthology.org/D19-1109)
- Language Models as Knowledge Bases. EMNLP/IJCNLP. 2019. [[paper]](https://doi.org/10.18653/v1/D19-1250)
- Designing Templates for Eliciting Commonsense Knowledge from Pretrained Sequence-to-Sequence Models. COLING. 2020. [[paper]](https://aclanthology.org/2020.coling-main.307/)
- Birds have four legs?! NumerSense: Probing Numerical Commonsense Knowledge of Pre-Trained Language Models. EMNLP. 2020. [[paper]](https://aclanthology.org/2020.emnlp-main.557/)
- How Can We Know What Language Models Know. TACL. 2020. [[paper]](https://transacl.org/ojs/index.php/tacl/article/view/1983)
- Knowledgeable or Educated Guess? Revisiting Language Models as Knowledge Bases. EMNLP/IJCNLP. 2021. [[paper]](https://doi.org/10.18653/v1/2021.acl-long.146)
- Factual Probing Is [MASK]: Learning vs. Learning to Recall. NAACL. 2021. [[paper]](https://arxiv.org/abs/2104.05240)
- A Systematic Investigation of Commonsense Knowledge in Large Language Models. EMNLP. 2022. [[paper]](https://arxiv.org/abs/2111.00607)
- Commonsense Knowledge Reasoning and Generation with Pre-trained Language Models: A Survey. AAAI. 2022. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21496)
- Does Pre-training Induce Systematic Inference? How Masked Language Models Acquire Commonsense Knowledge. NAACL. 2022. [[paper]](https://aclanthology.org/2022.naacl-main.337.pdf)


## 6. Neural Commonsense Knowledge Reasoning
- Commonsense Knowledge Base Completion. ACL. 2016. [[paper]](https://doi.org/10.18653/v1/p16-1137)
- Commonsense Knowledge Base Completion and Generation. CoNLL. 2018. [[paper]](https://doi.org/10.18653/v1/k18-1014)
- Commonsense Mining as Knowledge Base Completion? A Study on the Impact of Novelty. Workshop on Gen-Deep at ACL. 2018. [[paper]](http://dx.doi.org/10.18653/v1/W18-1002)
- Teaching Pretrained Models with Commonsense Reasoning: A Preliminary KB-Based Approach. Workshop on KR2ML at NeurIPS. 2019. [[paper]](https://arxiv.org/abs/1909.09743)
- COMET: Commonsense Transformers for Automatic Knowledge Graph Construction. ACL. 2019. [[paper]](https://doi.org/10.18653/v1/p19-1470)
  - (Comet-) Atomic 2020: On Symbolic and Neural Commonsense Knowledge Graphs. AAAI. 2021. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16792)
  - Symbolic Knowledge Distillation: from General Language Models to Commonsense Models. NAACL. 2022. [[paper]](https://doi.org/10.18653/v1/2022.naacl-main.341)
- Commonsense Knowledge Base Completion with Structural and Semantic Context. AAAI. 2020. [[paper]](https://aaai.org/ojs/index.php/AAAI/article/view/5684)
- Inducing Relational Knowledge from BERT. AAAI. 2020. [[paper]](https://aaai.org/ojs/index.php/AAAI/article/view/6242)
- Inductive Learning on Commonsense Knowledge Graph Completion. IJCNN. 2021. [[paper]](https://arxiv.org/abs/2009.09263)
- Commonsense Knowledge Reasoning and Generation with Pre-trained Language Models: A Survey. AAAI. 2022. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21496)
- CAKE: A Scalable Commonsense-Aware Framework For Multi-View Knowledge Graph Completion. AACL. 2022. [[paper]](https://doi.org/10.18653/v1/2022.acl-long.205)
- Learning from Missing Relations: Contrastive Learning with Commonsense Knowledge Graphs for Commonsense Inference. ACL(Findings). 2022. [[paper]](https://aclanthology.org/2022.findings-acl.119/)
- Commonsense Knowledge Base Completion with Relational Graph Attention Network and Pre-trained Language Model. CIKM(short). 2022. [[paper]](https://doi.org/10.1145/3511808.3557564)



