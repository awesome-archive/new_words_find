# new_words_find
# 新词发现／未登录词识别：
## 采用凝固度和左右信息熵规则来过滤，识别出新词。
## 执行python oov.py进行未登录词识别
# 同义词挖掘：
## 分词过滤后，简单采用word2vec进行挖掘，取topk人工审核后作为同义词。
## 执行train.sh挖掘同义词
