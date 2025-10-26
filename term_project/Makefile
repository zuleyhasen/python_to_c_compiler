all: lex yacc
	g++ lex.yy.c y.tab.c -ll -o project

yacc: prelab3.y
	yacc -d project.y

lex: prelab3.l
	lex project.l
clean: 
	rm lex.yy.c y.tab.c  y.tab.h  project


