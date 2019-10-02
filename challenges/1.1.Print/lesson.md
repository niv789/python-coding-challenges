## Print
- http://www.python-course.eu/python3_print.php
The print() function is used to present the output of a program.
Syntax: print(value(s), sep= ‘ ‘, end = ‘\n’, file=file, flush=flush)

Parameters:
value(s) : Any value, and as many as you like. Will be converted to string before printed
sep=’separator’ : (Optional) Specify how to separate the objects, if there is more than one.Default :’ ‘
end=’end’: (Optional) Specify what to print at the end.Default : ‘\n’
file : (Optional) An object with a write method. Default :sys.stdout
flush : (Optional) A Boolean, specifying if the output is flushed (True) or buffered (False). Default: False

```
>>> print(“Hello World”)
Hello World
```
It can have several parameters.
```
>>> print(‘Hello’,  12,  ‘98’)
Hello 12 98
```
The arguments of the print function:
sep=’’
Sep is a separator, it is used to divide parameters.
```
>>> print(‘Hello’, “World’, sep=’-‘)
Hello-World
```
We can assign an string to the keyword parameter "end". This string will be used for ending the output of the values of a print call.
end=’’
```
>>> print(‘Hello’, ‘World’, end=’!’)
Hello World?
```
By redefining the keyword parameter "file" we can send the output into a different stream file.
file=’’
```
>>> fh = open("data.txt","w")
>> print("no", file=fh)
>>> fh.close()
```
**_Instructions:_**
**Put your name and sname to appropriate places, change '*' to parameters of separator '_' and in the end of the line '!'.**
