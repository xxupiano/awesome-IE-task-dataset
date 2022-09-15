# IE tasks and datasets
studying...
- **OIE(Open Information Extraction)**
  OIE2016，WEB，NYT，PENN

- **NER(Named Entity Recognition)**

  NER类型

  - Flat NER: CoNLL-2003，OntoNotes
  - Nested NER: ACE 2004，ACE 2005，Genia
  - Discontinuous NER: CADEC，ShARe13，ShARe14

  资源多少

  - rich-resource domain: CoNLL-2003
  - cross-domain low-resource: MIT Restaurant Review，Airline Travel Information Systems(ATIS)，Few-NERD
  - MIT Movies

  domain

  - Bio: BC5CDR, JNLPBA, NCBI-disease
  - CS: SciERC

- **RE(Relation Extraction)**

  - sentence-level: SemEval 2010 Task-8, Wiki80 (from FewRel)，ACE 2003-2004，TACRED，FewRel
  - document-level：BC5CDR，DocRED
  - CDR (biomedical), GDA (biomedical)
  - NIST Automatic Content Extraction (ACE) RDC 2003 and 2004 corpora
  - DialogRE (each entity pair has more than one relation)
  - SciERC
  - **远程监督**
    - NYT corpus
    - NYT-10d (noisy test set, automatically annotated)
    - NYT-10m (manually annotated test set)
    - Wiki-20m (manually annotated test set)
    - RELX-Distant 多语言
    - Dis-ReX （多语言）

- **Relation Classification**
  TACRED，FewRel (few-shot), ChemProt(Bio), SciERC(CS)

- **Factual Probe**
  Google-RE，T-REx

- **Event Extraction**

  Document-level：ChFinAnn，DuEE-fin

- **NLI(Natural Language Inference)**

  1. also known as,  recognizing textual entailment, reading a pair of sentences and judging the relationship between them from one of `entailment, contradiction or neutral`
  2. Textual entailment is the task of determining whether a “hypothesis” is true, given a “premise”.

  SNLI (Stanford Natural Language Inference, approximately 550K hypothesis/premise pairs)，MultiNLI (MNLI)，Question NLI，RTE (from SuperGLUE)，SciTail, CB (3-way)

- **QA (Question Answering)**
  SQuAD, RACE，Story Cloze, ELI5

- **Question Classification**

  TREC (6-way)

- **Sentence Similarity**

  predicting whether two sentences are semantically equivalent or not

  MSR Paraphrase Corpus，Quora Question Pairs，STS Benchmark

- **Text Classification**
  Stanford Sentiment Treebank-2，CoLA, PaperField, SciCite, ACL-ARC(CS)

- **Topic Classification**

  AGNews, DBPedia

- **Sentiment Analysis**

  SST-2
  Stanford Sentiment Treebank (SST-5)

- **Semantic Role Labeling** (slot-filling or shallow semantic parsing)
  OntoNotes

- **Summarization**
  XSum (news summary), CNN/DM (news summary)

- **Fact Probe / Retrieval**

  LAMA

- **Coreference Resolution**
  OntoNotes

- **Dialogue**
  ConvAI2(dialogue response generation)

- **Dependency Parsing**
  domain

  - Bio: GENIA-LAS, GENIA-UAS

- **Other Corpus（一般用于预训练）**
  Wikipedia, BooksCorpus，1B Word Benchmark, OntoNotes, WikiText-103, Google Billion Word, WMT 2008-2012, CC-NEWS, OpenWebText

  [Wikitext2]([The WikiText Long Term Dependency Language Modeling Dataset (salesforceairesearch.com)](https://blog.salesforceairesearch.com/the-wikitext-long-term-dependency-language-modeling-dataset/)),

  GLUE

  RACE

  decaNLP
