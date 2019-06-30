---
title: 更新内容
tags: 更新说明,小书匠
grammar_mindmap: true
renderNumberedHeading: true
grammar_code: true
grammar_mathjax: true
---


[toc!?direction=lr]

# MultiOM
Source code and datasets for OM2019 research paper "Multi-view Embedding for Biomedical Ontology Matching "
# Code
the model in our experiment are in the following scripts:
ontomap.py
ontomap_syn.py
To train these model, please run；
train_ontomap.py
train_ontomap_syn.py
To evalute the effective of our model, please run the scripts in align_evalute:
align_onto.py
align_onto_syn.py
align_tfidf.py
align_onto_ontosyn.py
align_onto_ontosyn_tfidf.py
## Dependencies
Python 3
Tensorflow (>=1.2)
Numpy
# Datasets
In our experiment, we use the Medical Ontology FMA, NCI and MA.The detail of our datasets are in the floder Datasets, you can get the whole datasets in it.
## Directory structure
the train data are in the directory ../Datasets/DXX_UQU and ../Datasets/DXX_SYN


# Dataset files
# Running and parameters
Due to the instability of embedding-based methods, it is acceptable that the results fluctuate a little bit (±1%) when running code repeatedly.
# Citation
If you use this model or code, please cite it as follows:
Weizhuo Li, Xuxiang Duan, Meng Wang, XiaoPing Zhang, and Guilin Qi. Multi-view Embedding for Biomedical Ontology Matching. In: OM 2019.
