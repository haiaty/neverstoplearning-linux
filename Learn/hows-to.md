



## How to copy all files matching a pattern from dir 

```bash

find /src -type f -name '*.xml' -exec cp '{}' /dest ';'

```

-type f : indicates that we want only files

-name <pattern>: matches all files having the given pattern

-exec command ; The string '{}' is replaced by the current file name being processed. The specified command is run once for each matched file.



## How to Count the number of files in a directory

#### with pattern matching

```bash

find /dir -type f -name '*.zip' | wc -l

```

#### without pattern matching 

```bash

find /dir -type f | wc -l

```

-type f to include only files.

|  redirects find command's standard output to wc command's standard input.

wc (short for word count) counts newlines, words and bytes on its input (docs).

-l to count just newlines.

Notes:

Replace DIR_NAME with . to execute the command in the current folder.
You can also remove the -type f to include directories (and symlinks) in the count.
It's possible this command will overcount if filenames can contain newline characters.
