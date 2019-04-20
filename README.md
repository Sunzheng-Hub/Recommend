# analyzing-recommend-system
## 安装环境 
- Python 3.6 upper
- Numpy 1.4 upper

## 2019.04.20 update
- 矩阵奇异值分解（SVD）
    - [算法解析](https://github.com/ThomasHuai/Recommend/tree/master/matrix_factorization/svd)
    - [图片降噪](https://github.com/ThomasHuai/Recommend/tree/master/matrix_factorization/svd/image_denoising)
    - [Funk-SVD](https://github.com/ThomasHuai/Recommend/blob/master/matrix_factorization/svd/svd.pyx)

> 在推荐系统众多方法中，基于用户的协同过滤推荐算法是最早诞生的，原理也较为简单。该算法1992年提出并用于邮件过滤系统，两年后1994年被 GroupLens 用于新闻过滤。一直到2000年，该算法都是推荐系统领域最著名的算法。

> 所以说，当一个用户 A 需要个性化推荐时，可以先找到和他兴趣相似的用户群体 G，然后把 G 喜欢的、并且 A 没有听说过的物品推荐给 A，这就是基于用户的协同过滤算法。 根据上述基本原理，我们可以将基于用户的协同过滤推荐算法拆分为两个步骤：

> 1. 找到与目标用户兴趣相似的用户集合。
> 2. 找到这个集合中用户喜欢的、并且目标用户没有听说过的物品推荐给目标用户。

## run
```
python main.py
```
