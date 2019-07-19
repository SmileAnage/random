Python random函数
===

1.导入函数
>import random

2.相关函数

* 随机生成 0 到 1 的浮点数
>random.random()
>***e.g.*** print(random.random())

 * 随机生成指定范围的一个浮点数
 >random.uniform([ a, b ])
 >***e.g.*** print(random.uniform(1,20))

* 随机生成[ a, b ]范围中的一个数
>random.randint([ a, b ])
>***e.g.*** print(random.randint(1,10))

 * 随机生成[序列]中的指定个数的数
>random.sample( [序列], [nums] )
>***e.g.*** print(random.sample("abc", 1))

 * 随机生成[序列]中的一个数
 >random.choice()
 >***e.g.*** print(random.choice("abc"))
 
 * 对列表元素进行随机排列
 >random.shuffle( [序列] )
 >***e.g.*** random.shuffle( [1, 2, 3, 4, 5] )
