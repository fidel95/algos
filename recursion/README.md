# Recursion


###### examle below:

> this function gets a number
 ex: sumRange(5)
 then it checks if is greater than 0
 if it is then it adds up all the previous numbers from the number given
 ex: you give it a 5 it will yield 15 why?
 because it goes like: 5 + 4 + 3 + 2 + 1 = 15

```

function sumRangeRecursive(n, total = 0) {
    if (n <= 0) {
        return total
    }
    return sumRangeRecursive(n -1 ,total + n)
    
}
```