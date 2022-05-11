# GUIDE TO C


## to Print a statement
syntax: 
     
    printf("anything which you wanna print");
    
 example:
  
    printf("hello world");
output:
     
     hello world

\
\
\
use \n to go to a line 


\
example:
       
     printf("hello world\n hi there\n");
     printf("hi there?\n");
     printf("who are you");
output:
     
     hello world
     hi there
     hi there?
     who are you

\
\
there are some characters which cannot be printed directly and to print those characters we use an escape sequence '\\' followed by that character

\
for example
   
     printf("he said, \" hi there? \". ");
output
    
    he said, "hi there?".

characters which cannot be printed directly 

\\ = \\\
 
 " = \\"
 
 % = \\%
    
\
.
## data types
 data types is a specification of the data which you wanna store. for example: a number,a character,a decmimal number or  a sentence

## INTEGER or int
INTEGER is any whole number ranging from -2,147,483,648 to 2,147,483,647. decimal numbers are  not included in it.
### implementation
    int (variable name) = value;
for example 

    int a = 4;
    int b = 6;
### how to print an integer
    
    int a = 4;
    printf("Integer is %i", a);
        
#### OUTPUT
    Integer is 4
here %i is the format specifier for an integer
