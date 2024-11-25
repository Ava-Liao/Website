---
sidebar_position: 3
title: Object-Oriented Programming
---

# Q1: the difference between shallow and deep copy

## Shallow copy
Definition : A shallow copy creates a new object but inserts references into the original objects within the original data structure. Changes to nested objects will reflect in both the copied and original object.

Usecase: copy.copy()

## Deep copy
Definition : A deep copy constructs a new object and recursively inserts copies (not references) of objects found in the original. This means that changes to the copied object do not affect the original object.

Usecase: copy.deepcopy()

# Excercise
R2.1: life-critical software applications

R2.4 

```python

class flower :
    def __init__(self,name:str,petals:int,price:float):
        self._name = name
        self._petals = petals
        self._price = price
    
    def set_name(self,name:str):
        self._name = name
    def get_name(self):
        return self._name
    
    def set_petals(self,name:str):
        self._petals = petals
    def get_petals(self):
        return self._petals
    
    def set_price(self,price:float):
        self._price = price
    def get_price(self):
        return self.price
```

    