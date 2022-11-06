# algorithmic_complexity
analiza złożoności obliczeniowej

fibonacii iteracja
![fib_iter](https://user-images.githubusercontent.com/117569569/200169824-76b1e9b7-4bf8-418d-849e-f29206a075e2.png)
```py

def fibo(n):
    a = [0,1]
    i = 2
    while(i <= n):
        j = a[i-1] + a[i-2]
        a.append(j)
        print(a[i])
        i = i+1
        
    return a[n]
 ```
 
 
 
 fibonacci rekurencja
 
 ![fib_rek](https://user-images.githubusercontent.com/117569569/200169837-d0f35275-87ed-4b85-83d2-5f2f19094330.png)
 
 ```py
 def fib(n):
    if n<0:
        return False
    elif n == 0:
        return 1
    if n >= 2:
        return fib(n-1) + fib(n-2)
    else:
        return False
    
 ```
 
![porownanie it_rek](https://user-images.githubusercontent.com/117569569/200170404-a23d0657-7674-4f81-a013-245956d640ba.png)
Wykres przedstawia zależność czasu od liczby Fibonacciego. 
Kolor pomarańczowy - funkcja przy użyciu Fibonacciego rekurencyjnego
Kolor niebieski - funkcja przy użyciu Fibonacciego iteracyjnego 



