.PHONY: run

all: LabeledExprVisitor.py run
	python calc.py t.expr

LabeledExprVisitor.py: LabeledExpr.g4
	antlr4 -Dlanguage=Python3 -visitor -no-listener LabeledExpr.g4

