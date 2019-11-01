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
Flattening and sorting an array
```
const flattenAndSort = array => [].concat(...array).sort((a, b) => a - b) 
```
Password validator that is atleast six characters long, contains a lowercase letter, contains an uppercase letter, contains a number
```
const validate = password => /^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])[a-zA-Z0-9]{6,}$/.test(password)
```
Inverting a Hash or the keys and values of an object
```
const invertHash = hash => Object.keys(hash).reduce((obj, v) => (obj[hash[v]] = v, obj), {});

or

const invertHash = hash => {
  let result = {}
  for (let key in hash) {
    result[hash[key]] = key
  }
  return result
}
```
Removing duplicates in an array using Sets()
```
const removeDuplicateWords = s => [...new Set(s.split(' '))].join(' ')
```
Vowel Count in a string
```
const getCount = str => (str.match(/[aeiou]/gi) || []).length
```
Anagram Detection
```
const isAnagram = (test, original) => test.toLowerCase().split("").sort().join("") === original.toLowerCase().split("").sort().join("");
```
