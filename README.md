# Python Documentation
**Note:** The information provided here may or may not be correct as this is my interpretation of python code when learning from sources such as IITM DS Course, Sumita Arora and others...

## `print` function
Syntax:
`print(object(s), sep=separator, end=end, file=file, flush=flush)`

- Apart from `object(s)` all other parameters are optional
- By Default, `sep=' '` and `end='\n'`
    - Therefore, if you wish to not include spaces for only one set of objects we need to <font color=red>????????</font>

|Parameter|Description|Default|
|:-----:|:------|:------:|
|`object(s)`|Any object(s), which we wish to print. Will be converted to string before printed|-|
|`sep=`|Specifies how to seperate the objects, if multiple objects are present.|`sep=' '`|
|`end=`| Specifies how to end the print block after function execution is complete.|`end='\n'`
|`file`| An object with a write method.|`file=sys.stdout`
|`flush`| Boolean, specifying if the output is flushed (True) or buffered (False).|`flush=False`

## Data Types
### Variables
### Strings
### Literals
- The value that is constant cannot be changed
    - **e.g.** 2, 'Suresh', True, etc.
