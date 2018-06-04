# LL1-PARSER-IN-C
Automating the process of creating First and Follow sets and creating an LL1 Parsing Table
to check the validity of an user-input string according to given grammar.<br/>	
<br/>	
The grammar used is hard coded here.<br/>	 
But you can take you own grammar as an input storing it in C structures.<br/>	
Also, the code is very sequential and it should be easy to understand as it is a procedural implementation.<br/>	
<br/>	
NOTE:<br/>	
#Please check the size of your input string according to the code<br/>	
#Remember to add a '$' to the input string while entering the string to check<br/>
#'e' stands for epsilon<br/>	
<br/>	
GRAMMAR USED IN CODE(Feel free to add your own):<br/>	

E->TD<br/>	
D->+TD<br/>		
D->e<br/>		
T->FU<br/>	
U->*FU<br/>		
U->e<br/>		
F->(E)<br/>		
F->i<br/>		
