# PCA算法的实践
#### 主成分分析算法
PCA从n维减少到k维:
  1. 均值的归一化.需要计算出所有特征的均值,然后令xj=xj-uj(j代表第j维).但是当特征是不同数量级上的,还需要将其除以标准差.
  2. 计算协方差矩阵(covariance matrix).
  3. 计算协方差矩阵的特征向量.可以利用奇异值分解的方法来求解(singular value decomposition).
