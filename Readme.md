#Repository for testing jshell

------------------------------

##Errors
jshell> b = n;
|  Error:
|  incompatible types: possible loss
y conversion from int to byte
|  b = n;
|      ^

jshell> C = n;
|  Error:
|  cannot find symbol
|    symbol:   variable C
|  C = n;
|  ^

###After errors fixed
   
   3 : int n = 68;
   4 : byte b = 127;
   5 : char c ='B';
   6 : b = (byte)n;
   7 : c = (char)n;
