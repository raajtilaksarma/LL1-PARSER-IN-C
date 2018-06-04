# LL1-PARSER-IN-C
LL1 PARSER IN C FULL CODE
Automating the process of creating First and Follow sets and creating an LL1 Parsing Table
to check the validity of an user-input string according to given grammar.

The grammar used is hard coded here. 
But you can take you own grammar as an input storing it in C structures.
Also, the code is very sequential and it should be easy to understand as it is a procedural implementation.

NOTE:
#Please check the size of your input string according to the code
#Remember to add a '$' to the input string while entering the string to check
#'e' stands for epsilon

GRAMMAR USED IN CODE(Feel free to add your own):

E->TD	
D->+TD	
D->e	
T->FU	
U->*FU	
U->e	
F->(E)	
F->i	
