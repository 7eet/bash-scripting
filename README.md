## Bash Scripting Tutorial

### echo
	 _used to print data on the console._
	```
		echo "hello world"
	```
	
### comments
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
	
###  case statement 
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
