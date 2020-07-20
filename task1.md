笔记
-
[Datawhale零基础入门NLP赛事 - Task1 赛题理解](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.6.6406111aIKCSLV&postId=118252)

关键词：文本分类、字符识别

### 解题思路
思路1：TF-IDF + 机器学习分类器
直接使用TF-IDF对文本提取特征，并使用分类器进行分类。在分类器的选择上，可以使用SVM、LR、或者XGBoost。

[https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)

[https://scikit-learn.org/stable/modules/svm.html#svm](https://scikit-learn.org/stable/modules/svm.html#svm)

[https://www.kaggle.com/stuarthallows/using-xgboost-with-scikit-learn](https://www.kaggle.com/stuarthallows/using-xgboost-with-scikit-learn)

思路2：FastText
FastText是入门款的词向量，利用Facebook提供的FastText工具，可以快速构建出分类器。

[https://fasttext.cc/](https://fasttext.cc/)

思路3：WordVec + 深度学习分类器
WordVec是进阶款的词向量，并通过构建深度学习分类完成分类。深度学习分类的网络结构可以选择TextCNN、TextRNN或者BiLSTM。

[https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa](https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa)

思路4：Bert词向量
Bert是高配款的词向量，具有强大的建模学习能力。

[https://github.com/google-research/bert](https://github.com/google-research/bert)

