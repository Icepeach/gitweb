# Gitweb
This project is amended from gitweb component of Git for Windows (version 2.16.1).

## Requirements
- Apache 2.4
- Git for Windows 2.16.1
- ActivePerl 5.22

## Changes

### gitweb.cgi

1. set file location of the perl interpreter (first line)
2. set the core git executable file name
3. Comment all of references of macro S_ISLINK
4. List projects manually with owners to avoid to invoke function getpwuid.

## Web test
Open http://127.0.0.1/git to see the result.

(to be continued)
