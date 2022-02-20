# python4prfessionals

#### run command as a string
```
$ python -c 'print("hello, sensei")'
```

Rules for variable naming:
1. Variables names must start with a letter or an underscore.
```
x = True # valid
_y = True # valid


9x = False # starts with numeral
=> SyntaxError: invalid syntax
$y = False # starts with symbol
=> SyntaxError: invalid syntax
```
2. The remainder of your variable name may consist of letters, numbers and underscores.
```
has_0_in_it = "Still Valid"
```
3. Names are case sensitive.
```
x = 9
y = X*5
=>NameError: name 'X' is not defined
```