# PyDocs
Useful Docs for Python

* [Asterisks](https://github.com/ahsanarshad1993/PyDocs/blob/master/README.md#asterisks-in-python-what-they-are-and-how-to-use-them)
* [zip()](https://github.com/ahsanarshad1993/PyDocs/blob/master/README.md#using-the-python-zip-function-for-parallel-iteration)
* [repr()](https://github.com/ahsanarshad1993/PyDocs/blob/master/README.md#python-repr)
* [Python pass Statement](https://github.com/ahsanarshad1993/PyDocs/blob/master/README.md#python-pass-statement)


### Asterisks in Python: what they are and how to use them:
https://treyhunner.com/2018/10/asterisks-in-python-what-they-are-and-how-to-use-them/

```
>>> numbers = [2, 1, 3, 4, 7]
>>> more_numbers = [*numbers, 11, 18]
>>> print(*more_numbers, sep=', ')
2, 1, 3, 4, 7, 11, 18
```

 - Using * and ** to pass arguments to a function
 - Using * and ** to capture arguments passed into a function
 - Using * to accept keyword-only arguments
 - Using * to capture items during tuple unpacking
 - Using * to unpack iterables into a list/tuple
 - Using ** to unpack dictionaries into other dictionaries


### Using the Python zip() Function for Parallel Iteration
https://realpython.com/python-zip-function/

```sh
numbers = [1, 2, 3]
letters = ['a', 'b', 'c']
zipped = zip(numbers, letters)
print(list(zipped))
```

OUTPUT: ```[(1, 'a'), (2, 'b'), (3, 'c')]```


### Python repr()
https://www.programiz.com/python-programming/methods/built-in/repr

The repr() function returns a printable representation of the given object.

```
var = 'foo'
print(repr(var))
```

```
'foo'
```

### Python pass Statement
https://www.tutorialspoint.com/python/python_pass_statement.htm
