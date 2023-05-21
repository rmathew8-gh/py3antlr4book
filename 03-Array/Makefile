all:
	antlr4 -Dlanguage=Python3 ArrayInit.g4 -visitor -o py

tt:
	(cd py; pygrun ArrayInit init --tokens ../input.txt)
	(cd py; pygrun ArrayInit init --tree ../input.txt)

test:
	python test_array.py input.txt
	@#PYTHONPATH=py python test_array.py input.txt
