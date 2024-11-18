---
sidebar_position: 2
title: Python Primer
---

### Q1 Why bool,int,float,str,tuple,frozenset are immutable?
Initially, I thought bool,int,float are mutable, let's see the code:
```python
a = 1
a += 1
print(a)
```
The result of a is 2, which means the value of a is changed.But the type of a is still int.

But,  "a class is immutable if each object of that class has a fixed value upon instantiation that cannot subsequently be changed." Let's see the code:
```python
a = 10
print(id(a))
a += 1
print(id(a))
```
the result is:
```
140734261726800
140734261726832
```
the id of a is changed, which means the value of a is changed.

### Q2 Int()
use int() will return the value based upon an existing value of another type.For example: 
int(1.12) =1, int(-1.99) =-1,int(-3.01)=-3, and int()=0
the trucated part is the integer part of the value.

### Q3 Tuple class
when there is only one element in the tuple, like(1,), we must use a comma, otherwise, it will be int type, and becomes (1).

### Q4 Yield
The defference between return and yield: the yield is forward-looking and the return is backward-looking.

So it means that, yield allow to step by step to aquire the results, but the return must gain the results right away.




