



## How to copy all files matching a pattern from dir 

```bash

find /src -type f -name '*.xml' -exec cp '{}' /dest ';'

```

-type f : indicates that we want only files

-name <pattern>: matches all files having the given pattern

-exec command ; The string '{}' is replaced by the current file name being processed. The specified command is run once for each matched file.
