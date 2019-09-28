# interview
- 面试要点整理

## 一句话总结

### word2vec
kip-gram：基于负采样使用中心词预测上下文，不断调整中心词的词向量，实现序列向量化；
CBOW：使用上下文预测中心词，梯度同等作用到上下文中；

### Transformer
基于自注意力机制提取序列的特征，扩展到多头提取不同角度的信息，可以并行；

### GBDT
基于加法模型，多轮迭代，不断减少训练过程中的伪残差来实现数据分类和回归的算法，自带平方损失。

### XGBoost
GBDT的工程实现，做了部分优化：显式正则，二阶信息，特征并行排序，线性模型；

### FM
实现特征二阶交叉，简化复杂度


- 场景业务
- 团队定位于目标
- 期望产出
- highcount

![](knowledge.png)