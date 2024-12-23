
You need to add these 4 functions in your public portion of your class HashTable. These 4 functions are:
- `insert()`
- `remove()`
- `search()`
- `printTable()`


Assume all numbers entered into the table are non-negative numbers. The table should resize to **at least** twice of the previous size in case the threshold is crossed. The new size as mentioned should be a **prime number** as well.

`insert()` and `remove()` functions should be as taught by Professor in class and should not return anything or print the table. 
`search()` should return (not print) the index at which the value was found. Return -1 if not found.
`printTable()` should behave the following way: 

If the table of size 7 contains value 2 at the 4th position and value 17 at the 6th position the printTable should print (be mindful of the extra space at the end):

```
- - - 2 - 17 - 
```

- In case of insert exceeding the maximum quadratic probing you can do, you should print "Max probing limit reached!" in a new line.
- In case duplicate keys are being entered you program should print "Duplicate key insertion is not allowed" in a new line.
- In case the element to be removed was not found you should print "Element not found" in a new line.

An example run could be:
```
- - - - - 
- 1 - - - 
- 1 - 4 -
Element not found
Duplicate key insertion is not allowed
2 1 - 4 - 
```
