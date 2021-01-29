# PL
Record the whole writing PL progress. PL(Program Language) is the most important course in my college. 
To keep track of my PL progress.

## Project 1

Key word: 

1. QUIT: "quit"
2. IDENT: letter + digits  or  letter + letters  or  letter + '_'  !!Can not be "quit"
3. NUM:  Integer or float number( 35, 7, 48.3, .35, 1.0 and 07)
4. line comment


Grammer:
<command> ::= IDENT ( ':=' <ArithExp> | <IDlessArithExpOrBexp> ) ';'
                           | <NOT_IDStartArithExpOrBexp> ';'
                           | QUIT
                           
<IDlessArithExpOrBexp> ::=  
