# algorithmic_complexity
analiza złożoności obliczeniowej
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
 
