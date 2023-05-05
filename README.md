# SMD-based-DCTAs-oriented-public-attitudes-assessment-approach

# !!! As the paper is under review, all contents in this repository currently are not allowed to be re-used by anyone until this announcement is deleted.

1. General introduction
1.1 This repository aims at providing the codes and data regarding the paper entitled “……” for the public.

1.2 All codes are developed on Python 3.6, and the IDE adopted is PyCharm. The codes also support the GPU computing for higher speed.

1.3 We greatly appreciate the selfless spirits of these voluntary contributors of a series of open python libraries, including Bert (https://github.com/google-research/bert), Tensorflow (https://github.com/tensorflow/models), pytorch (https://github.com/pytorch/pytorch), Keras (https://github.com/keras-team/keras), Numpy (https://numpy.org/), labelImg (https://github.com/tzutalin/labelImg), pyExcelerator (https://github.com/WoLpH/pyExcelerator), py2neo (https://github.com/py2neo-org/py2neo), some base works (https://github.com/yongzhuo/Keras-TextClassification, https://github.com/brightmart/text_classification), and so on. 

1.4 All of codes have been tested to be well-performed. Even so, we are not able to guarantee their operation in other computing environments due to the differences in the python version, computer operating system, and adopted hardware.

2 The specifications of critical codes
2.1 Packages
gensim==3.7.1

jieba==0.39
numpy==1.16.2
pandas==0.23.4
scikit-learn==0.19.1
tflearn==0.3.2
tqdm==4.31.1
passlib==1.7.1
keras==2.2.4
keras-bert==0.41.0
keras-xlnet==0.16.0
keras-adaptive-softmax==0.6.0

2.2 Download data
(a) Go to this link to download embeddings: https://pan.baidu.com/s/184yyTUWJyTSpgw-1KN0EFw (extract code:8k6e)
(b) Extract the downloaded files and place them in 'keras_textclassification/data/embeddings' 

2.3 Usage
(a) Enter 'keras_textclassification/m00_Bert'
(b) Training and validation: run train.py
(c) Test: run predict.py

2.4 Use your own data
Replace data in 'keras_textclassification/data/multi_category' (or 'keras_textclassification/data/multi_label'), and make sure that the format remains the same as the example.

2.5 Adjust hyperparameters
Please adjust the hyperparameters according to Table S4.
