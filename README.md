# PRIME NUMBERS FUNCTION
 A prime number is a number that is divisible by 1 or by itself.Prime numbers begin from 2

```python
def is_prime(n):
        status = True
        if n < 2:
            status = False#checks if the the number is less than 2 
        else:
            for i in range(2,n):#returns True if the number is divisible by itself,meaning it is a prime number
                if n % i == 0:
                    status = False
        return status
for n in range(0,101):
    if is_prime(n):
        if n==97:
            print n
        else:
print n,",",
```
