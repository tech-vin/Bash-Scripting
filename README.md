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
 
