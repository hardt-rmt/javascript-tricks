Multiplying each of the numbers in an array using reduce
``` 
const grow = x => x.reduce((result, n) => result * n, 1) 
```
Multiplying each of the numbers in an array using eval
``` 
const fill = y => eval(y.join("*")) 
```
Getting the sum of all positive numbers in an array using reduce
``` 
const ps = arr => arr.reduce((sum, n) => n > 0 ? sum + n : sum, 0) 
```
Basic Math operation using eval
``` 
const basicOp = (operation, value1, value2) => eval(value1 + operation + value2) 
```
Getting items in an array whose length are equal to 4 using filter
```
const friend = friends => friends.filter(i => i.length === 4)
```
Adding two numbers together and returning their sum in binary
```
const addBinary = (a, b) => (a + b).toString(2)
```
