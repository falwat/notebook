# Notebook for Python

---
## Python 语法
- ** 注释 **
```
 # File : test.py
 # creat by Jackie Wang
```

- ** 列表 ** 

列表中的元素类型可以不同
```
a = [1 , 2.3 , 'hello world']
```
列表可以嵌套
```
a = [1 , 2 , [31 , 32 , 33],4]
```
对列表中的每个元素进行简单运算可以：
```
a = range(10)
b = [k**2 for k in a]
```

---
## IPython

-  ** 运行一个文件 **
```
run test.py
```

- ** 编辑脚本 **
```
%ed test.py # or
%edit test.py # % 可以省略
```
## numpy
- ** 数组 **
```
import numpy as np //

```