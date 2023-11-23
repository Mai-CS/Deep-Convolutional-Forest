# Deep convolutional forest: a dynamic deep ensemble approach for spam detection in text
Mai A. Shaaban, Yasser F. Hassan, Shawkat K. Guirguis

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/deep-convolutional-forest-a-dynamic-deep/ensemble-learning-on-sms-spam-collection-data)](https://paperswithcode.com/sota/ensemble-learning-on-sms-spam-collection-data?p=deep-convolutional-forest-a-dynamic-deep)
[![Static Badge](https://img.shields.io/badge/Paper-Link-yellowgreen?link=https%3A%2F%2Fzenodo.org%2Frecords%2F10104139)](https://link.springer.com/article/10.1007/s40747-022-00741-6)
[![python](https://img.shields.io/badge/Python-3.8-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![tensorflow](https://img.shields.io/badge/TensorFlow-1.12-FF6F00.svg?style=flat&logo=tensorflow)](https://www.tensorflow.org)

## Abstract
The increase in people’s use of mobile messaging services has led to the spread of social engineering attacks like phishing, considering that spam text is one of the main factors in the dissemination of phishing attacks to steal sensitive data such as credit cards and passwords. In addition, rumors and incorrect medical information regarding the COVID-19 pandemic are widely shared on social media leading to people’s fear and confusion. Thus, filtering spam content is vital to reduce risks and threats. Previous studies relied on machine learning and deep learning approaches for spam classification, but these approaches have two limitations. Machine learning models require manual feature engineering, whereas deep neural networks require a high computational cost. This paper introduces a dynamic deep ensemble model for spam detection that adjusts its complexity and extracts features automatically. The proposed model utilizes convolutional and pooling layers for feature extraction along with base classifiers such as random forests and extremely randomized trees for classifying texts into spam or legitimate ones. Moreover, the model employs ensemble learning procedures like boosting and bagging. As a result, the model achieved high precision, recall, f1-score and accuracy of 98.38%.

<br>
Figure 1: Workflow of data: text preprocessing, word embedding, feature extraction and classification

<img src="Figures/workflow.png" width="500" style="background-color:white;"/>

<br>
Figure 2: Structure of Deep Convolutional Forest (DCF)

<img src="Figures/DCF structure.png" width="500" style="background-color:white;"/>
<br>

# Usage
This project was prepared to run on Colab

To use the code on Colab:
1. Uncomment the following in cell #5 to download GloVe embeddings

	`!wget http://nlp.stanford.edu/data/glove.6B.zip`

	`!unzip -q glove.6B.zip`

2. Change the data and the embeddings directories in cell #2 and #6:

	`/content/drive/My Drive/Shared DCF/`

# Cite
<pre><code>
@article{Shaaban2022,
	title        = {Deep convolutional forest: a dynamic deep ensemble approach for spam detection in text},
	author       = {Shaaban, Mai A. and Hassan, Yasser F. and Guirguis, Shawkat K.},
	year         = 2022,
	month        = {Apr},
	day          = 26,
	journal      = {Complex {\&} Intelligent Systems},
	doi          = {10.1007/s40747-022-00741-6},
	issn         = {2198-6053},
	url          = {https://doi.org/10.1007/s40747-022-00741-6},
	abstract     = {The increase in people's use of mobile messaging services has led to the spread of social engineering attacks like phishing, considering that spam text is one of the main factors in the dissemination of phishing attacks to steal sensitive data such as credit cards and passwords. In addition, rumors and incorrect medical information regarding the COVID-19 pandemic are widely shared on social media leading to people's fear and confusion. Thus, filtering spam content is vital to reduce risks and threats. Previous studies relied on machine learning and deep learning approaches for spam classification, but these approaches have two limitations. Machine learning models require manual feature engineering, whereas deep neural networks require a high computational cost. This paper introduces a dynamic deep ensemble model for spam detection that adjusts its complexity and extracts features automatically. The proposed model utilizes convolutional and pooling layers for feature extraction along with base classifiers such as random forests and extremely randomized trees for classifying texts into spam or legitimate ones. Moreover, the model employs ensemble learning procedures like boosting and bagging. As a result, the model achieved high precision, recall, f1-score and accuracy of 98.38{\%}.}
}
</code></pre>
