# Bash

#### Open with `vi` the third line from `locate <file>`

```bash
$ vi $( locate <file> | head -n3 | tail -n1 )
```

> Caveat: No newlines in the filenames, please. :)

[Source](http://unix.stackexchange.com/questions/189704/open-a-result-of-locate-with-vi/189714#189714)
