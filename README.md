# Bash-Scripting

## Hello Bash Scripting

- which bash
- cd Desktop
- touch helloscript.sh
- vi helloscript.sh

```
#! /usr/bin/bash
hello vineet!
```
- save and quit (:wq)
- chmod -x helloscript.sh
- ./helloscript.sh

## Redirect to file

- creating a new file with "Hi vineet" in it.
- if the file is already present then it will replace the text to given one.

```
#! /usr/bin/bash

echo "Hi vineet" > output.txt

```

- creating a new file but this time user will be able to feed in the input.
- all the information will be recorded in the output.txt
- use ```ctlr + D``` to save & terminate.
- Running the script again will replace the previous text.

```
#! /usr/bin/bash

cat > output.txt
```

- This senerio is similar to the previous but this time if user runs the script again and feeds in new data then it will be added to the previous data.
- We are appending data 

```
#! /usr/bin/bash

cat >> output.txt

```

## Adding Comments

- comment is the instructions added for the programmer's understanding
- single line command can be applyed using ```#``` as the prefix
```
#! /usr/bin/bash/

# hi this is a single line comment
# these won't appear in the output
```
- Multiline comment are used to display comments that consume more than one line.
```
#! /usr/bin/bash/

: '
These are multiline comments
these comments will not appear in the output
make sure you hit a space after colon. '
```

- To show the comment message in the output we use a delimeter.

```
#! /usr/bin/bash/

cat << variable
Hello, all of these text 
will appear in the output.
to stop, we have to write variable again.
you can give any name instead of vaiable
variable

```
## Conditional Statements

- ne - not equal to
- eq - equal to
- gt - greater than
- <  - smaller than
- >  - greater than
- if
- then
- elif
- else

```
#! /usr/bin/bash

count=10

if [ $count -ne 10 ]
then
	echo "not equal to 10"

```

- with else condition

```
#! /usr/bin/bash

count=10


```
 
