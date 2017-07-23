Project: Password Table Generator   
Version 1.0   
Release date: 2012-10-31   
State: stable   

## Description:

Generate, store and print stored password tables.   
Read John Graham-Cumming's article ["Write your passwords down"](http://blog.jgc.org/2010/12/write-your-passwords-down.html).

## Dependencies:

binutils

## Documentation:

-g TableName : Generate password table TableName.
-p TableName : Print password table TableName.
-l : List all existing password tables.

## Installation:

Put this script somewhere in your $PATH (~/bin is a good choice). Make it executable with chmod.
If you want bash tab completition put file psstbl_tab in /etc/bash_completition.d/ and rename it to psstbl.
