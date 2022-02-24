# Information Extraction Datasets Collections

欢迎大家贡献公开信息抽取数据集（尤其是.中文.信息抽取数据集）

---
2022-02-24-Updated:
TODO:  
- [ ] 为中文和英文数据集分别建立一份文档
- [ ] 为每份数据集，提供相关论文介绍
- [ ] 使用预处理的代码进行处理好。
- [ ] 统计实体的类型 +数据集的划分
- [ ] 处理好的上传Drive提供下载链接
    
---
## Named Entity Recognition

| Datasets | Domain | Language | Intro | Ent Types | PaperWithCode | Train/Dev/Test(Preprocess Code) | Download |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CoNLL02 | News | English |  |  |  |  | [download](https://www.clips.uantwerpen.be/conll2002/ner/) |
| CoNLL03 | News | English |  |  |  |  | [download](https://www.clips.uantwerpen.be/conll2003/ner/) |
| ConNLL03 | News | English |  | LOC、ORG、PER、MISC |  | [doc](https://catalog.ldc.upenn.edu/docs/LDC2013T19/OntoNotes-Release-5.0.pdf) | [download](https://www.clips.uantwerpen.be/conll2003/ner/) |
| CoNLL 2017 | News |  | Multilingual: has developed treebanks for 40+ languages with cross-linguistically consistent annotation and recoverability of the original raw texts |  |  |  | [download](https://aclweb.org/portal/content/conll-2017-shared-task-multilingual-parsing-raw-text-universal-dependencies) |
| Cross-lingual Name Tagging| Wiki | 282 Languages|  |  |  | [doc](https://aclanthology.org/P17-1178.pdf) | [download](http://nlp.cs.rpi.edu/wikiann) |
| OntoNotes4.0 | News | English,Chinese,Arabic |  | PERSON、NORP、 LOC、 GPE、 PRODUCT、 EVENT、LAW |  | [doc](https://catalog.ldc.upenn.edu/docs/LDC2011T03/OntoNotes-Release-4.0.pdf) | [download](https://catalog.ldc.upenn.edu/LDC2011T03) |
| OntoNotes5.0 | News | English, Chinese,Arabic |  |  |  |  | [download](https://catalog.ldc.upenn.edu/ldc2013t19) |
| NNE [2019] | News | English | A Dataset for Nested Named Entity Recognition in English Newswire |  |  |  | [download](‣) |
| MSRA | 新闻 | 中文 |  | 人物、地点、机构 |  |  | [download](https://github.com/GuocaiL/nlp_corpus/tree/main/open_ner_data/MSRA) |
| WeiBo | 微博 | 中文 |  | 地名、人名、机构名、行政区名 |  |  |  |
| Resume | 简历 | 中文 |  | 人名、国籍、籍贯、种族、专业、学位、机构、职称 |  |  | [download](https://github.com/GuocaiL/nlp_corpus/tree/main/open_ner_data/ResumeNER) |
| BosonNER | 新闻 | 中文 |  | 时间、地点、人名、组织名、公司名、产品名 |  |  | [download](https://github.com/GuocaiL/nlp_corpus/tree/main/open_ner_data/boson) |
| ClueNER | 新闻 | 中文 |  | 组织、人名、地址、公司、政府、书籍、游戏、电影、职位、景点 |  |  | [download](https://github.com/GuocaiL/nlp_corpus/tree/main/open_ner_data/cluener_public) |
| People Daily | 新闻 | 中文 |  | 地名、机构名、人名 |  |  | [download](https://github.com/GuocaiL/nlp_corpus/tree/main/open_ner_data/people_daily) |
| CCKS2019-Task1 | 电子病历 | 中文 | CCKS2019评测任务一，即“面向中文电子病历的命名实体识别”的数据集 | 实验室检验、影像检查、手术、疾病和诊断、药物、解剖部位 |  |  | [download](https://github.com/GuocaiL/nlp_corpus/tree/main/open_ner_data/yidu-s4k) |
| CCKS2020-Task |  | 中文 | 面向试验鉴定的命名实体数据集 | 试验要素、性能指标、系统组成、任务场景 |  |  | [download](https://www.biendata.xyz/competition/ccks_2020_8/) |
| CCKS2017-2020 | 电子病历 | 中文 |  | 症状和体征、检查和检验、疾病和诊断、治疗、身体部位 |  |  | [download](https://www.biendata.xyz/competition/CCKS2017_2) |
| CCKS2018 | 电子病历 | 中文  |  | 解剖部位、症状描述、独立症状、药物、手术 |  |  | [download](https://www.biendata.xyz/competition/CCKS2018_1) |
| CCKS2019 | 电子病历 | 中文 |  | 疾病、诊断、检查、检验、手术、药物、解剖部 |  |  | [download](https://github.com/GuocaiL/nlp_corpus/tree/main/open_ner_data/2020_ccks_ner。) |
| CCKS2020 | 电子病历 | 中文 |  | 疾病、诊断、检查、检验、手术、药物、解剖部位 |  |  | [download](https://www.biendata.xyz/competition/ccks_2020_2_1/) |


## Relation Extraction


| Datasets | Domain | Language | Introduction | Rel Types | PaperWithCode | Train/Dev/Test(Preprocess Code) | Download |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ACE04 |  | English |  |  |  | 常用的分割方式：[link1](https://github.com/dwadden/dygiepp), [link2](https://github.com/LorrinWWW/two-are-better-than-one)) | [download](https://catalog.ldc.upenn.edu/LDC2005T09) |
| ACE05 |  | English |  |  |  | 常用的分割方式：[link](https://github.com/lavis-nlp/spert) | [download](https://catalog.ldc.upenn.edu/LDC2006T06) |
| Conll04 | News | English |  |  |  |  | [download](http://lavis.cs.hs-rm.de/storage/spert/public/datasets/conll04/) |
| GENIA | Bio | English | The GENIA corpus is the primary collection of biomedical literature compiled and annotated within the scope of the GENIA project. The corpus was created to support the development and evaluation of information extraction and text mining systems for the domain of molecular biology.|  |  |  | [download] |
| ADE | Bio , Drug  | English | a benchmark corpus to support the automatic extraction of drug-related adverse effects from medical case reports. |  |  | 注意这里是使用十折交叉验证 | [download](http://lavis.cs.hs-rm.de/storage/spert/public/datasets/ade/) |
| Chempot | BioPapers | English | ChemProt consists of 1,820 PubMed abstracts with chemical-protein interactions annotated by domain experts and was used in the BioCreative VI text mining chemical-protein interactions shared task. |  |  |  | [download](https://biocreative.bioinformatics.udel.edu/news/corpora/chemprot-corpus-biocreative-vi/) |
| SciERC | SciPapers | English |  |  |  |  | [download](http://lavis.cs.hs-rm.de/storage/spert/public/datasets/scierc/) |
| DialogRE | Film | English,Chinese | The first human-annotated dialogue-based relation extraction dataset, containing 1,788 dialogues originating from the complete transcripts of a famous American television situation comedy Friends. |  |  | 5,936 / 1,928/1,858  (36 rels)           | [download](https://dataset.org/dialogre/) |
| DocRED | News | English | DocRED是基于维基百科的文档级关系抽取数据集，数据集中每个文档都被标注了命名实体提及、核心参考信息、句内和句间关系以及支持证据。关系类型涉及科学、艺术、时间、个人生活在内的96种Wikidata关系类型。 |  |  |  | [download](https://huggingface.co/datasets/docred) |
| TACRED | News | English | TACRED is a large-scale relation extraction dataset with 106,264 examples built over newswire and web text. Examples in TACRED cover 41 relation types as used in the TAC KBP challenges   |  |  | | [download](https://nlp.stanford.edu/projects/tacred/) |
| CDR | Sci-Biometrics | English | a human-annotated dataset in the biomedical domain. It consists of 500 documents for train- ing. The task is to predict the binary interactions between Chemical and Disease concepts. |  |  | 数据预处理处理：[link](https://github.com/fenchri/edge-oriented-graph) | [download]() |
| GDA | Sci-Biometrics | English | a large-scale dataset in the biomedical domain. It contains of 29,92 articles.The task is to predict the binary interactions between Gene and Disease concepts. |  |  | 数据预处理：[link](https://github.com/fenchri/edge-oriented-graph) | [download]() |
| SciREX | Sci-CS | English | SCIREX is a document level IE dataset that encompasses multiple IE tasks, including salient entity identification and document level N-ary relation identification from scientific articles. The dataset is annotated by integrating automatic and human annotations, leveraging existing scientific knowledge resources |  | [sota](https://paperswithcode.com/dataset/scirex) | 数据预处理：[link] | [download](https://github.com/allenai/SciREX/blob/master/scirex_dataset/release_data.tar.gz) |
| SciCN | Sci-CS | 中文 |  |  |  |  | [download] |
| NYT-10 | Wiki | English | 由NYT corpus 在2010年基于Freebase远程监督得到的，共包含founders、place_of_birth在内的53种关系（包括一种NA |  |  | 数据划分和预处理: [CasRel](https://github.com/weizhepei/CasRel) | [download](https://github.com/thunlp/OpenNRE/blob/master/benchmark/download_nyt10.sh) |
| WebNLG | Wiki | English | the WebNLG challenge consists in mapping data to text. The training data consists of Data/Text pairs where the data is a set of triples extracted from DBpedia and the text is a verbalisation of these triples |  |  | 数据划分和预处理：[CasRel](https://github.com/weizhepei/CasRel) | [download](https://drive.google.com/file/d/1zISxYa-8ROe2Zv8iRc82jY9QsQrfY1Vj/view) |
| SemEval-2010-Task8 | News | English | SemEval数据集是2010年国际语义评测大会中Task8任务所使用的数据集，该数据集包括8000个训练样本，2717个测试样本 |  | [link](https://paperswithcode.com/dataset/semeval-2010-task-8) |  | [download](https://github.com/thunlp/OpenNRE/blob/master/benchmark/download_semeval.sh) |
| FewRel | Wiki |  English | 该数据集包括100个关系类别、70,000个关系实例。每句的平均长度为24.99 |  |  |  | [download](https://github.com/thunlp/OpenNRE/blob/master/benchmark/download_fewrel.sh) |
| Wiki80 | Wiki | English | Wiki80是从数据集FewRel上提取的一个关系数据集，共包含location、part of、follows等80种关系，每种关系个数均为700，共56000个样本。 |  |  |  | [download](https://github.com/thunlp/OpenNRE/blob/master/benchmark/download_wiki80.sh) |
| DuIE2.0 | 新闻 | 中文 | 数据集包含超过43万三元组数据、21万中文句子及48个预定义的关系类型 |  |  |  | [download](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/examples/information_extraction/DuIE) |
| CCKS2019 | 电子病历 | 中文 | 层级关系分类任务，包括三大类(亲属关系、社交关系、师生关系)，四中类(配偶、血亲、姻亲、友谊）、35小类(现夫、前妻)种关系类型 |  |  |  | [download](https://github.com/SUDA-HLT/IPRE) |
| Chinese Literature Text | 文学作品 | 中文 | 面向中文文学的一个实体关系数据集，标注了物体、人名、地名、时间名、容量名、组织和摘要共7类实体，位于、部分、家庭、概括、社会、拥有、使用、制造、邻接等9类实体关系 |  |  |  | [download](https://github.com/lancopku/Chinese-Literature-NER-RE-Dataset/tree/master/relation_extraction) |
## Event Extraction

- TODO

## ToolKit

| ToolKit |  Intro | Repo |
| --- | --- | --- |
| Spacy | 英文NLP工具 | [homepage](https://github.com/explosion/spaCy) |
| FastHAN | 中文NLP工具 | [homepage](https://github.com/fastnlp/fastHan) |
| HanNLP | 中文NLP工具 | [homepage](https://github.com/hankcs/HanLP) |
| ZJU-DEEPKG | 知识图谱抽取 | [homepage](https://github.com/zjunlp/DeepKE) |
| THU-NRE | 信息抽取工具 | [homepage](https://github.com/thunlp/OpenNRE) |

## More Datasets

| Forum | Intro |  Websit |
| --- | --- | --- |
| Huggface Datasets |  | https://huggingface.co/datasets?sort=downloads&search=web |
| Github |  |  |
| Kaggle |  |  |

## Contact
 - 📧yangjing2036@126.com