## 函数的组合参数
- 组合参数的顺序:位置参数、默认参数、可变参数、命名关键字参数、关键字参数
- 可变参数和命名关键字参数不能同时出现
- 组合参数最复杂的使用情况为如下两种:
def func1(name, age=21, *args, **kwargs):
    print(name, age, args, kwargs)
    
def func2(name, age=21,  *, height, weight, **kwargs):
    print(name, age, height, weight, kwargs)

- 以下两种组合参数用法，系统报错，语法错误   
def func3(name, age=21, *args, *, height, weight):
    print(name, age, args, height, weight)
    
def func4(name, age=21, *args, *, height, weight, **kwargs):
    print(name, age, args, height, weight, kwargs)
    
- To be continue！