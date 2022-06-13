#Abstract

Cancer research, including that of breast cancer, has increasingly relied on molecular profiling based on advances in genomic technology. Although these techniques have permitted scientists to unravel the process by which cancer develops, scientists still struggle to effectively translate the vast amounts of patient data into clinically meaningful results. As a result, tasks such as predicting the human response to differing treatments still remains a major challenge in cancer treatment.

Many studies have been conducted to determine the survival indicators that a patient with breast cancer may exhibit. However, most of these analyses were predominantly performed using traditional statistical methods, which was both time-consuming and imperfect in tackling the vast amounts of data there is on breast cancer. But, with the advent of computing power and new ideas about artificial intelligence, I believe that there is an opportunity for machine learning to supersede our current capabilities in fully understanding the correlations between geneset mutations, drug responses, and the prognosis of breast cancer. This information would greatly benefit scientists in developing clinical strategies, such as performing personalized treatment. 

This machine learning project employs numerous machine learning approaches, including a novel deep learning algorithm, in building models for the detection and visualization of significant prognostic indicators of breast cancer survival rate. The clinical and genomic data of 1,980 primary breast cancer sample used in this project were obtained from the Molecular Taxonomy of Breast Cancer International Consortium (METABRIC) database of cBioPortal. The data was preprocessed and then split to train eight classical machine learning models and the aforementioned deep learning CNN model. 

These models were evaluated using the recall score, the accuracy score, the receiver operating characteristic (ROC) curve, and the area under the ROC curve (AUC) on the training dataset and confirmed using the rest of the data of the dataset. Both the deep learning and machine learning methods produced desirable prediction accuracies, but the deep learning model noticeably outperformed all other classifiers and achieved the highest accuracy (AUC = 0.902). This project was constructed in the Google Colab environment based on python and its programming libraries with data visualization, Tensorflow, and Keras.

#Methodology

Step 1: Identification of a machine learning problem: how to accurately predict the survivor rate of breast cancer patients.
Step 2: Identification of relevant dataset to be analyzed. The dataset used in this project is the METABRIC (Molecular Taxonomy of Breast Cancer International Consortium) database from cBioPortal.
Step 3: Data Preprocessing and Gene-Set Signature Identification

#Conclusion

The deep learning CNN model produced a 21 gene signature for the prediction of human breast cancer survival. The mRNA levels (mutations?) of these genes correlate well with breast cancer patients’ prognosis and histopathology. This gene set offers a statistically significant predictive value with an AUC (Area Under Curve) score of 0.902, indicating our model is an excellent discriminatory model.