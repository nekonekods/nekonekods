# 我的Python笔记
![image](https://i0.hdslb.com/bfs/article/fc67ed65ab9c1cf033158857d4a6db9e993446dc.jpg@722w_1016h_progressive.webp)
> 记得打空格
## 基础语句
- 条件
```
if 条件
    语句
elif 条件
    语句
其他
```
## List
示例：
```
list2 = [1, 2, 3, 4, 5 ]
list3 = ["a", "b", "c", "d","e","f"]
list2[2]  # 2
list3[2:4]  # ["c", "d"] 
list3[1:-2]  # ["b", "c", "d","e"]
list3[1:]  # ["b", "c", "d","e","f"]
```
要点：
1. 正向下标是0基，反向下标是-1基
![image](https://www.runoob.com/wp-content/uploads/2014/05/positive-indexes-1.png)
![image](https://www.runoob.com/wp-content/uploads/2014/05/negative-indexes.png)

2. 截取前闭后开

## Math常用函数
> 小写m
```
    math.fabs(x)  #绝对值
    math.ceil(x)  #向上取整
    math.floor(x)  #向下取整
    math.sqrt(x)  #平方根
    
    三角函数（反三角前加a）
    
    math.exp(x)  #e的x次幂
    math.log(x[, base])
    #使用一个参数，返回 x 的自然对数（底为 e ）
    #使用两个参数，返回给定的 base 的对数 x ，计算为 log(x)/log(base)
    
    a**b  #a的b次幂
    
```
