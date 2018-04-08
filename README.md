# Multilabel-classification-
Multilabel classification with scikit-learn (python) 


机器学习模型进行multi-lable分类（一级标签），步骤：
1. 读取数据，并将数据切分至train data、cross validation data、test data
2. 文本向量化：onehot与tfidf
3. 模型训练：多标签模型knn、svm
4. 交叉验证cross validation，选择优参数
5. 用test data 输出不同模型的准确度，给出展示。

# 模型精度

模型 and F1值 | onehot| tfidf| word2vec(100维) | word2vec(100 标准化) 
---|---|---|---|---
knn | 45% （k=7)| 58% （k=11)| 57% （k=3)| 54% （k=9)
线性核svm | 40%| 61% | 50% | 59% 
决策树 | 43%| 60%| 55%| 55%