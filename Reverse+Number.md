

```python
# REVERSING THE DIGITS
def Reverse_Order(x):
    #Bust a move right here
    if x >= 0:
        y = 0   
        while x != 0:
            y = y*10 + x%10
            x = int(x/10)
    return y

print("Desc",Reverse_Order(195678))
```

    Desc 876591
    
