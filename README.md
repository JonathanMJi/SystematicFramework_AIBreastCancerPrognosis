# breast-cancer-analysis
Our deep learning CNN model produced dataset with 31 clinical attributes and a 21 gene signature for the prediction of human breast cancer survival. Besides the clinical attributes, the mRNA levels (mutations?) of these genes correlate well with breast cancer patients’ prognosis and histopathology. This gene set offers a statistically significant predictive value with an AUC (Area Under Curve) score of ROC
(Receiver Operating Characteristic) curve of 0.831, indicating our model is an excellent discriminatory model.

These 21 genes include BRCA1, BRCA2, PALB2, PTEN, TP53, CDH1, ATM, CHEK2, STK11, BARD1, CASP8, CYP19A1, MAP3K1, NF1, NBN, TERT, PIK3CA,
RAD51C, EGFR, MLH1, MSH2. Previous studies have shown that mutations in these genes indicate increased risks of human hereditary breast cancer. Moreover, mutations in
PTEN and PIK3CA are correlated with worse and better survival in breast cancer patients, respectively. Additionally, amplification of TERT gene copies and increased
EGFR gene expression are associated with worse prognosis in breast cancer patients.

However, these studies focused mutations in only some of these genes, and no studiers have used these 21 genes together as a gene signature. Importantly, our study reveals that not only mutations, but the mRNA levels of these genes have great potential to predict potential survival.

We consider that this type of deep learning model has great potential for predicting breast cancer patient survival. Importantly, the approach we have used in this study can be utilized to model patient survival in other human cancers.

