---
sidebar_position: 5
title: Recursion
---

The classic example: caculate the n! I think his explanation is very easy to understand, you need to read it by yourself.I saw many explanation, but I understand little.

And this explanation help me to understand--https://learn.lianglianglee.com/%e4%b8%93%e6%a0%8f/%e9%87%8d%e5%ad%a6%e6%95%b0%e6%8d%ae%e7%bb%93%e6%9e%84%e4%b8%8e%e7%ae%97%e6%b3%95-%e5%ae%8c/11%20%20%e9%80%92%e5%bd%92%ef%bc%9a%e5%a6%82%e4%bd%95%e5%88%a9%e7%94%a8%e9%80%92%e5%bd%92%e6%b1%82%e8%a7%a3%e6%b1%89%e8%af%ba%e5%a1%94%e9%97%ae%e9%a2%98%ef%bc%9f.md

``` python
def factorial(n):
    if n==0:
        return 1
    else:
        return n*factorial(n-1)
```

The key to writing recursive code lies in formulating the recurrence relation and identifying the termination condition.

## Excercise

R4.1
```python

def get_max(S,n):
    if n==1:
        return S[0]
    else:
        return max(S[n-1],get_max(S,n-1))
```

R4.2 
```python
def power(x,n):
    if n==0:
        return 1
    else:
        return x*power(x,n-1)
```

I finish some leetcode problem, and feel more confident.