#  This repository is to collect BERT related resources.

# Papers: 

arXiv:1810.04805, https://arxiv.org/abs/1810.04805, 

BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding

Authors: Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova

Abstract: We introduce a new language representation model called BERT, which stands for Bidirectional Encoder Representations from Transformers. Unlike recent language representation models, BERT is designed to pre-train deep bidirectional representations by jointly conditioning on both left and right context in all layers. As a result, the pre-trained BERT representations can be fine-tuned with just one additional output layer to create state-of-the-art models for a wide range of tasks, such as question answering and language inference, without substantial task-specific architecture modifications. BERT is conceptually simple and empirically powerful. It obtains new state-of-the-art results on eleven natural language processing tasks, including pushing the GLUE benchmark to 80.4% (7.6% absolute improvement), MultiNLI accuracy to 86.7 (5.6% absolute improvement) and the SQuAD v1.1 question answering Test F1 to 93.2 (1.5% absolute improvement), outperforming human performance by 2.0%. 

# Github Repositories: 

## official implement:

1. ` google-research/bert  , https://github.com/google-research/bert,  **officical** TensorFlow code and pre-trained models for BERT `


## implement of BERT besides tensorflow: 

1. codertimo/BERT-pytorch, https://github.com/codertimo/BERT-pytorch,   Google AI 2018 BERT pytorch implementation

2. ` huggingface/pytorch-pretrained-BERT ,  https://github.com/huggingface/pytorch-pretrained-BERT,   A PyTorch implementation of Google AI's BERT model with script to load Google's pre-trained models  `  

3. Separius/BERT-keras, https://github.com/Separius/BERT-keras, Keras implementation of BERT with pre-trained weights, [**325 stars**]

4. soskek/bert-chainer,  https://github.com/soskek/bert-chainer,  Chainer implementation of "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding"

5. innodatalabs/tbert, https://github.com/innodatalabs/tbert, PyTorch port of BERT ML model

6. guotong1988/BERT-tensorflow, https://github.com/guotong1988/BERT-tensorflow, BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding

7. dreamgonfly/BERT-pytorch, https://github.com/dreamgonfly/BERT-pytorch, 
PyTorch implementation of BERT in "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" 

8. CyberZHG/keras-bert, https://github.com/CyberZHG/keras-bert, Implementation of BERT that could load official pre-trained models for feature extraction and prediction

9. soskek/bert-chainer, https://github.com/soskek/bert-chainer, Chainer implementation of "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding"

10. MaZhiyuanBUAA/bert-tf1.4.0, https://github.com/MaZhiyuanBUAA/bert-tf1.4.0, bert-tf1.4.0


## other resources for BERT: 

1.  hanxiao/bert-as-service,   https://github.com/hanxiao/bert-as-service,    Mapping a variable-length sentence to a fixed-length vector using pretrained BERT model   

2. brightmart/bert_language_understanding,  https://github.com/brightmart/bert_language_understanding, Pre-training of Deep Bidirectional Transformers for Language Understanding: pre-train TextCNN

3. Y1ran/NLP-BERT--ChineseVersion,  https://github.com/Y1ran/NLP-BERT--ChineseVersion, 谷歌自然语言处理模型BERT：论文解析与python代码
, [**83 stars**]

4. algteam/bert-examples, https://github.com/algteam/bert-examples

5. yuanxiaosc/Deep_dynamic_word_representation, https://github.com/yuanxiaosc/Deep_dynamic_word_representation, TensorFlow code and pre-trained models for deep dynamic word representation (DDWR). It combines the BERT model and ELMo's deep context word representation.

6. yangbisheng2009/cn-bert, https://github.com/yangbisheng2009/cn-bert, BERT在中文NLP的应用

7. JayYip/bert-multiple-gpu, https://github.com/JayYip/bert-multiple-gpu, A multiple GPU support version of BERT, [**8 stars**]

8. xu-song/bert_as_language_model, https://github.com/xu-song/bert_as_language_model, bert as language model, fork from https://github.com/google-research/bert, [**5 stars**]

9. whqwill/seq2seq-keyphrase-bert, https://github.com/whqwill/seq2seq-keyphrase-bert, add BERT to encoder part for https://github.com/memray/seq2seq-keyphrase-pytorch

10. HighCWu/keras-bert-tpu, https://github.com/HighCWu/keras-bert-tpu, Implementation of BERT that could load official pre-trained models for feature extraction and prediction on TPU

11. Willyoung2017/Bert_Attempt, https://github.com/Willyoung2017/Bert_Attempt, 

12. Pydataman/bert_examples, https://github.com/Pydataman/bert_examples, some examples of bert, run_classifier.py 是基于谷歌bert实现了Quora Insincere Questions Classification二分类比赛。run_ner.py是基于瑞金医院AI大赛 第一赛季数据和bert写的一个命名实体识别。

13. guotong1988/BERT-chinese, https://github.com/guotong1988/BERT-chinese, BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding 中文 汉语

14. zhongyunuestc/bert_multitask, https://github.com/zhongyunuestc/bert_multitask, 多任务task



## BERT QA task:

1. benywon/ChineseBert, https://github.com/benywon/ChineseBert, This is a chinese Bert model specific for question answering

2. vliu15/BERT, https://github.com/vliu15/BERT, Tensorflow implementation of BERT for QA

3. benywon/ChineseBert, https://github.com/benywon/ChineseBert, This is a chinese Bert model specific for question answering

4. xzp27/BERT-for-Chinese-Question-Answering, https://github.com/xzp27/BERT-for-Chinese-Question-Answering, 

## BERT classification task:

1. zhpmatrix/Kaggle-Quora-Insincere-Questions-Classification, https://github.com/zhpmatrix/Kaggle-Quora-Insincere-Questions-Classification, Kaggle新赛(baseline)-基于BERT的fine-tuning方案+基于tensor2tensor的Transformer Encoder方案

2. maksna/bert-fine-tuning-for-chinese-multiclass-classification, https://github.com/maksna/bert-fine-tuning-for-chinese-multiclass-classification, use google pre-training model bert to fine-tuning for the chinese multiclass classification

3. NLPScott/bert-Chinese-classification-task, https://github.com/NLPScott/bert-Chinese-classification-task, bert中文分类实践, [**51 stars**]

4. Socialbird-AILab/BERT-Classification-Tutorial, https://github.com/Socialbird-AILab/BERT-Classification-Tutorial, [**151 stars**]

5. fooSynaptic/BERT_classifer_trial, https://github.com/fooSynaptic/BERT_classifer_trial, BERT trial for chinese corpus classfication

6. xiaopingzhong/bert-finetune-for-classfier, https://github.com/xiaopingzhong/bert-finetune-for-classfier, 微调BERT模型,同时构建自己的数据集实现分类


## BERT  NER  task:  

1. JamesGu14/BERT-NER-CLI, https://github.com/JamesGu14/BERT-NER-CLI, Bert NER command line tester with step by step setup guide

2. zhpmatrix/bert-sequence-tagging, https://github.com/zhpmatrix/bert-sequence-tagging, 基于BERT的中文序列标注

3. kyzhouhzau/BERT-NER, https://github.com/kyzhouhzau/BERT-NER, Use google BERT to do CoNLL-2003 NER !  [**120 stars**]

4. king-menin/ner-bert, https://github.com/king-menin/ner-bert, NER task solution (bert-Bi-LSTM-CRF) with google bert https://github.com/google-research.

5. macanv/BERT-BiLSMT-CRF-NER, https://github.com/macanv/BERT-BiLSMT-CRF-NER, Tensorflow solution of NER task Using BiLSTM-CRF model with Google BERT Fine-tuning  , [**145 stars**]

6. FuYanzhe2/Name-Entity-Recognition, https://github.com/FuYanzhe2/Name-Entity-Recognition, Lstm-crf,Lattice-CRF,bert-ner及近年ner相关论文follow, [**3 stars**]

7. mhcao916/NER_Based_on_BERT, https://github.com/mhcao916/NER_Based_on_BERT, this project is based on google bert model, which is a Chinese NER

8. ProHiryu/bert-chinese-ner, https://github.com/ProHiryu/bert-chinese-ner, 使用预训练语言模型BERT做中文NER



## BERT  Knowledge Graph Task : 

1. lvjianxin/Knowledge-extraction, https://github.com/lvjianxin/Knowledge-extraction, 基于中文的知识抽取，BaseLine：Bi-LSTM+CRF 升级版：Bert预训练


