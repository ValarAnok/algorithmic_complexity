# algorithmic_complexity
analiza złożoności obliczeniowej

##fibonacii iteracja
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
 ##fibonacci rekurencja
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
 
![szybki fib](https://user-images.githubusercontent.com/117569569/200168552-e30d0e48-5c96-4127-bed5-578bf5efc5e2.png)
![wolny fib](https://user-images.githubusercontent.com/117569569/200168554-9aedb796-7abc-4199-8c1f-624df950bfd5.png)
