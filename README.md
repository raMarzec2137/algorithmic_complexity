# algorithmic_complexity
comparing various computation complexities
```py
def fib2(n):
    i = 0
    a = 1
    b = 1
    lst=[]
    while i < n // 2:
        lst.append(a)
        lst.append(b)
        #print(a , b)
        i = i + 1
        c = a + b
        a = b
        b = c
    return lst
    ```py
