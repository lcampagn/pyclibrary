PyClibrary
==========

C parser and ctypes automation for Python.

Fork of <https://launchpad.net/pyclibrary>. 

PyCLibrary includes 1) a pure-python C parser and 2) a ctypes automation library
that uses C header file definitions to simplify the use of ctypes. The C parser
currently processes all macros, typedefs, structs, unions, enums, function 
prototypes, and global variable declarations, and can evaluate typedefs down to
their fundamental C types + pointers/arrays/function signatures. Pyclibrary can 
automatically build ctypes structs/unions and perform type conversions when 
calling functions via cdll/windll.
