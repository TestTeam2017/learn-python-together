python的基本数据类型分为以下几种:
- 数字(**numerics**)
- 序列(**sequences**)
- 映射(**mappings**)
- 类(**classes**)
- 实例(**instances**)
- 异常(**exceptions**)
# 数字
python中的数据主要包括:
- 布尔
```
is_exist = False
is_contain = True
```
- 整型(**int**)
```
age = 20
i = 0xff
j = 032
```
- 浮点型(**float**)
```
score = 98.5
fi = .5
fj = 2.
```
- 复数(**complex**)
```
ci = 2 + 3j
```
# 序列
python中的序列主要包括:
- 字符串(**str**)
```
email = 'zhangsan@gmail.com'
```
- 列表(**list**)
```
url_list = ['https://www.baidu.com/', 'https://cn.bing.com/']
```
- 元组(**tuple**)
```
default_names = ('lisi', 'zhangsan')
```
- 范围(**range**)
```
range(10)
```
# 映射
python中的映射主要包括:
- 字典(**dict**)
```
books = {'id': 10001, 'name': 'name_of_book'}
```
- 集合(**set**)
```
names = set(['zhangsan', 'lisi'])
fruits = frozenset(['apple', 'orange'])
```
# 类
```
class People(object):
    pass
```
# 实例
# 异常
[异常继承树](https://docs.python.org/3/library/exceptions.html#exception-hierarchy)

**注**

python中的类型由编译器自动推导, 无需指定类型说明符.
```
int i = 2  # error
i = 2      # ok
```
#表示行注释
