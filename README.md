### About

Copy the last modified file from the given directory to the working directory. Optionally, a file can be renamed. Multiple files are supported without rename option.

This script will automatically create clfconfig.conf file with the default source directory:
 `~/Downloads`

I have used (for learning purposes) Google's style guide available on their [GitHub](https://google.github.io/styleguide/shellguide.html)

### Usage
Usage template:

`$ bash cplf [flag] [optional]`

Add script to `/usr/local/bin` and `sudo chmod +x clf` to have it in PATH.

### Help info:
```
This script will operate on files in a source directory specified by -d flag.

-h  Print help.

-d  Print the current source directory.
    + [directory path] Change source directory.

-c  Copy recursively the last modified file to a working directory.
    + [file name] Copy and rename.

-m  Move the last modified file to a working directory.
    + [file name] Move and rename.
```