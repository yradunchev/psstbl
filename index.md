Project: Password Table Generator   
Version 1.0   
Release date: 2012-10-31   
State: stable   

-------------------------------------------------------------------------------
Description:

Generate, store and print stored password tables ([tabula recta](http://en.wikipedia.org/wiki/Tabula_recta)) from CLI.   

The idea behind the tool and how to use the tables best described by John Graham-Cumming in his article ["Write your passwords down"](http://blog.jgc.org/2010/12/write-your-passwords-down.html).

See also ["Vigenère cipher"](http://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher)


-------------------------------------------------------------------------------
Dependencies:

* binutils

-------------------------------------------------------------------------------
Documentation:

-g TableName : Generate password table TableName.   
   If there is existing table with that name it will be preserved.

-p TableName : Print password table TableName.

-l	: List all existing password tables. 
 
-------------------------------------------------------------------------------
Installation instructions

Put this script somewhere in your $PATH (~/bin is a good location). Make it executable with chmod.
If you want bash tab completition to work with the script - put file psstbl_tab in /etc/bash_completition.d/ and rename it to psstbl.
