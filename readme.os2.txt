This is the OS/2 port of GIFtrans 1.12, a program for converting GIF files to
GIF89a by Andreas Lea (ley@rz.uni-karlsruhe.de).  The program was compiled
using emx/gcc 0.9aPL5 and requires the emx runtime dll (available on OS/2 ftp 
sites as emxrt.zip).  GIF89a supports transparent backgrounds, a nice feature 
in these days of WWW pages.  I've also included a formatted man page, since 
many OS/2 users do not have a man program.  Copyrights are held by Andreas 
Lea.  See the giftrans.c file for more information.  I include getopt.c for 
completeness; it is not needed when compiling with gcc, but apparently some
other compilers may require it.

Clark Gaylord
cgaylord@vt.edu
5 August 1995
