## 1、变量的创建和赋值 ##

在 Python 程序中，变量是用一个变量名表示，可以是任意数据类型，变量名必须是大小写英文、数字和下划线（_）的组合，且不能用数字开头，
注意一点是 Python 是不用声明数据类型的。在 Python 中 `=` 是赋值语句，跟其他的编程语言也是一样的，因为 Python 定义变量时不需要声明数据类型，因此可以把任意的数据类型赋值给变量，且同一个变量可以反复赋值，而且可以是不同的数据类型。
这种变量本身类型不固定的语言称之为动态语言，与之对应的是静态语言。静态语言在定义变量时必须指定变量类型，如果赋值的时候类型不匹配，就会报错。例如 Java 是静态语言。
## 2、多个变量赋值 ##
Python 允许同时为多个变量赋值。例如：
```python
a = b = c = 1
```
以上实例，创建一个整型对象，值为 1，三个变量被分配到相同的内存空间上。
当然也可以为多个对象指定多个变量。例如：
```python
a, b, c = 1, 2, "liangdianshui"
```
以上实例，两个整型对象 1 和 2 的分配给变量 a 和 b，字符串对象 "liangdianshui" 分配给变量 c。
