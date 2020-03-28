## Bash Scripting Tutorial

### Echo
_used to print data on the console._
```
	echo "hello world"
```
	
### Comments
_used to give information about script or a statement._
	 
- **single line comment** - _use ->  `#` to comment_
	```
		# single line comment 
	```
- **multiline comment** -  _use ->   `:' enter your comment here '`._
	```	
		:' 
		this
		is 
		a 
		multi 
		line 
		comment
		'
	```
	
### Case statement 
_It like a switch statements in other programming language._
```
case $var in 
	case1 ) echo "Hello :)" ;;
	case2 ) echo "HIII :)" ;;
	* ) echo "hii" ;;
esac
```
_example:_
```
name="h"
case $name in
	"g" ) echo "G" ;;
	"h" ) echo "H" ;;
	*) echo "1" ;;
esac
```

### Conditional statements

#### if-else
_syntax_
```
	if [ condition ]; then
		# statements
	else
		# statements
	fi
```

**OR**

```
	if [ condition ]; then
		#statements
	elif [ condition ]; then
		#statements
	else 
		#statements
	fi
```

### Expressions
#### File
| Expression      | Is true if |
| --------------- | ---------- |
| file1 -eq file2 | file1 and file2 have same inode number |
| file1 -nt file2 | file1 is newer than file2 |
| file1 -ot file2 | file1 is older than file2 |
| -d file         | file exists and is a directory |
| -e file         | file exists |
| -f file         | file exists and is a regular file |
| -r file         | file exists and is readable |
| -w file         | file exists and is writable |
| -x file         | file exists and is executable |
| -s file         | file exists and has a length greater then zero |

#### String
| Expression         | Is true if |
| ----------         | ---------- |
| -n string          | the length of string is > 0 |
| -z string          | the length of string is zero |
| string1 == string2 | string1 and string2 are equal |
| string1 != string2 | string1 and string2 are not equal |

#### Integer
| Expression | Is true is |
| ---------- | ---------- |
| integer1 -eq integer2 | integer1 is equal to integer2 |
| integer1 -ne integer2 | integer1 is not equal to integer2 |
| integer1 -le integer2 | integer1 is less than or equal to integer2 |
| integer1 -lt integer2 | integer1 is less then integer2 |
| integer1 -ge integer2 | integer1 is greater than or equal to integer2 |
| integer1 -gt integer2 | integer1 is greater than integer2 |

