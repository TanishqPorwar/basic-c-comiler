compile:
	@lex lexl.l
	@yacc -d parser.y -v
	@gcc -w -g y.tab.c -ll -o parser

