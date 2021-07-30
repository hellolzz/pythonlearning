# tuple（元组） #
tuple 和 List 非常类似，但是 tuple 一旦初始化就不能修改。
元组（tuple） 不可变是指当你创建了 tuple 时候，它就不能改变了，也就是说它也没有 append()，insert() 这样的方法，但它也有获取某个索引值的方法，但是不能赋值。
创建空元组
```python
tuple3=()
```
元组中只包含一个元素时，需要在元素后面添加逗号

```python
tuple4=(123,)
```

如果不加逗号，创建出来的就不是 元组（tuple），而是指 ```123``` 这个数了。
元组下标索引也是从 0 开始，元组（tuple）可以使用下标索引来访问元组中的值。

```python

tuple1=('两点水','twowter','liangdianshui',123,456)
tuple2='两点水','twowter','liangdianshui',123,456

print(tuple1[1])
print(tuple2[0])
```
tuple 元组中的元素值是不允许删除的，但我们可以使用 del 语句来删除整个元组

```python

tuple1=('两点水','twowter','liangdianshui',[123,456])
print(tuple1)
del tuple1
```
与字符串一样，元组之间可以使用 `+` 号和 `*` 号进行运算。这就意味着他们可以组合和复制，运算后会生成一个新的元组。

|Python 表达式|结果|描述|
|-----------|-----|-----|
|len((1, 2, 3))|3|计算元素个数|
|(1, 2, 3) + (4, 5, 6)|(1, 2, 3, 4, 5, 6)|连接|
|('Hi!',) * 4|('Hi!', 'Hi!', 'Hi!', 'Hi!')|复制|
|3 in (1, 2, 3)|True|元素是否存在|
|for x in (1, 2, 3):  print(x)|1 2 3|迭代|

|方法|描述|
|----|----|
|len(tuple)|计算元组元素个数|
|max(tuple)|返回元组中元素最大值|
|min(tuple)|返回元组中元素最小值|
|tuple(seq)|将列表转换为元组|
