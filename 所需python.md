深度学习所需python

`package_name.function()` #调用某库中的某函数function

```  python
math.exp() #输入参数为实数
numpy.exp() #输入参数可以为矩阵、向量
```



list只支持len()

numpy.array同时支持len, size, shape

numpy.sum 默认参数下把所有元素相加，但可指定axis
```
>>>np.sum([[0, 1], [0, 5]], axis=0)
array([0, 6])

>>>np.sum([[0, 1], [0, 5]], axis=1)
array([1, 5])
```

np.multiply：*加上广播功能等价于np中的multiply The * operator can be used as a shorthand for np.multiply on ndarrays.


