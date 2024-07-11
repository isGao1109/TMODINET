# TMODINET: A Trustworthy Multi-Omics Dynamic Learning Integration Network for Cancer Diagnostic
Ling Du, Peipei Gao, Zhuang Liu, Nan Yin, and Xiaochao Wang

TMODINET is a trustworthy multi-omics dynamic learning framework for cancer diagnostic.

![TMODINET](https://github.com/isMery0123/TMODINET/blob/master/TMODINET/TMODINET.png)
Overview of TMODINET. \
<sup>Framework of TMODINET. (a) The whole framework of the model. TMODINET is a trusted framework based on dynamic learning that integrates multiple omics data for cancer diagnosis. (b) Modality Dynamic Learning Module based on a single-peak classifier. Triple contrastive learning is used to learn comparisons between multiple omics and achieve inter-omics alignment. Modality confidence learning assigns different weights to omics to indicate their different contributions to the final result. (c.FDLM) Feature Dynamic Learning Module allocates sample adaptive weights to each feature instead of relying on fixed weight vectors. (c.GDLM) Graph Dynamic Learning Module can adjust the structure of the graph adaptively according to the classification results and realize the dynamic graph structure for specific graph convolutional networks (GCN) learning.<sup>

## Files
*main.py*: Examples of TMODINET for classification tasks\
*models.py*: TMODINET model\
*train_test.py*: Training and testing functions\
*layers.py*: Supporting functions\
*utils.py*: Supporting functions\
  

