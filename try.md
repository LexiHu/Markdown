# 输出了第10个斐波那契数列
代码如下
```
def fib(n):
    a, b = 1, 1
    for i in range(n-1):
        a, b = b, a+b
    return a
print fib(10)
```
