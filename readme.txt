incl 1.0
--------

This is a header file that can be used in programs to save bytes of code space.

If you use in() and out() together, you will have to enter two #include- directives like

  #include "in.cpp"
  #include "out.cpp"
  
additionally to the

  #include <stdio.h>
  
which is needed in any case because in() and out() won't work without it.

So the saving of code space will be gone immediately in very small programs.

So you can use just

  #include "incl.h"
  
which includes the files

  stdio.h
  in.cpp
  out.cpp
  
by itself with just one #include- directive in your program.



Version history
---------------

Version 1.0

Initial version

