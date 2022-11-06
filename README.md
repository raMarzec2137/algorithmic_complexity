# algorithmic_complexity
comparing various computation complexities


## Iteracyjny Fibonacci 
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
    
```

## Rekurencyjny Fibonnaci
```py
def badfib(n):
    if n == 0:
        return 1
    if n == 1:
        return 1
    return badfib(n-1) + badfib(n-2) 
```
Wzrost czasu jest wprost proporcjonalny do wzrostu wartości dla itaracyjnego , podczas gdy dla reurencyjnego wzrost jest zbyt gwałtowny.
![wykres](https://user-images.githubusercontent.com/117570347/200169224-906ee24f-f13c-4007-905b-6b966b7af65a.png)
