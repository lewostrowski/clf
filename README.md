### About

Copy last modified file from given directory to working direcotry. Optionally, a file can be renamed. Multiple files are supported without rename option.

This script will automatically creates clfconfig.conf file with default source directory:
 `~/Downloads`

### Usage
Usage template:

`$ bash cplf [flag] [optional]`

### Help info:
```
This script will operate on files in a source directory specified by -d flag.

-h  Print help.

-d  Print current source directory.
     + [directory path] Change source directory.

-c  Copy recursively last modified file to a working directory.
    + [file name] Copy and rename.

-m  Move last modified file to a working directory.
    + [file name] Move and rename.
```