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
![liniowy1](https://user-images.githubusercontent.com/117570347/200165973-e43fb2b4-d7aa-4697-9d85-a50f2615f81a.jpg)
![liniowy1](https://user-images.githubusercontent.com/117570347/200166219-3b0a724f-bae7-4935-ae18-1beba093d050.jpg)
![wykres](https://user-images.githubusercontent.com/117570347/200169224-906ee24f-f13c-4007-905b-6b966b7af65a.png)
