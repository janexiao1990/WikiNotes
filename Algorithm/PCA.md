# 降维
## 主成分分析 （PCA）
Principal Component Analysis

在PCA中，数据从原来的坐标系转换到了新的坐标系。新坐标系的选择是由数据本身决定的。
第一个新坐标轴选择的是原始数据中方差最大的方向，第二个新坐标轴选择和第一个坐标轴正交且具有最大方差的方向。该过程一直重复。重复次数为原始数据中特征的数目。

可以发现，大部分方差都包含在最前面的几个新坐标轴中。因此可以忽略后面的坐标轴，从而实现了降维处理。

优点：降低数据复杂性，识别最重要的多个特征。
缺点：不一样需要，可能损失有用信息。
适用数据类型：数值型数据。