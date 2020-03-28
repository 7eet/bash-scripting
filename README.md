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
