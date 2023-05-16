all:
	antlr4 -Dlanguage=Python3 Hello.g4 -visitor -o py

tokens:
	(cd py; pygrun Hello r --tokens ../input.txt)

tree:
	(cd py; pygrun Hello r --tree ../input.txt)

test:
	PYTHONPATH=py python test_hello.py input.txt
