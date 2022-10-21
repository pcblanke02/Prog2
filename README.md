# Prog2
Program 2 "Pretty Print"

Before proceeding, ensure that Flex and Bison are installed on your device.

Type the following commands into the terminal while in program directory:

  flex p2.l
  
  gcc lex.yy.c error.c init.c symbol.c -o pprint
  
 ./pprint < p2test-fixit.c > output.html
