# 從...導入...
from pandas import Series

# 先建立一個list
a = [1, 2, 3, 4]

# 序列化索引
s = Series(a)

# 索引用法
s.index
s.values

# 更改序列化索引方式
s1 = Series(a, index=['A','B','C','D'])
