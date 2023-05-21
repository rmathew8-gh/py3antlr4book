.PHONY: run

all: LabeledExprVisitor.py run
	python calc.py t.expr

LabeledExprVisitor.py: LabeledExpr.g4
	antlr4 -Dlanguage=Python3 -visitor -no-listener LabeledExpr.g4


# 	antlr4-parse LabeledExpr.g4 prog -tokens t.expr
# 	antlr4-parse LabeledExpr.g4 prog -tree t.expr

# JAR=/home/roy/Downloads/Antlr/antlr-4.12.0-complete.jar

# java/NowebLexer.class: NowebLexer.g4
# 	java -Xmx500M -cp "${JAR}:${CLASSPATH}" org.antlr.v4.Tool -o java NowebLexer.g4
# 	java -Xmx500M -cp "${JAR}:${CLASSPATH}" org.antlr.v4.Tool -o java NowebParser.g4
# 	javac -cp "${JAR}:${CLASSPATH}" src/Noweb*.java


# grun: NowebLexer.class
# 	java -Xmx500M -cp "${JAR}:${CLASSPATH}" org.antlr.v4.gui.TestRig LabeledExpr prog -tokens t.expr

# .PHONY: gen-py pytest

# all: gen-py pytest

# gen-py: pyx/NowebLexer.py

# pyx/NowebLexer.py: NowebLexer.g4 NowebParser.g4
# 	antlr4 -Dlanguage=Python3 NowebParser.g4 NowebLexer.g4 -visitor -o pyx

# pytest:
# 	py.test -x -s -n0 '.'

# cmnts:
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tokens test-inputs/input.cmnts
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tree test-inputs/input.cmnts

# bad-cmnts:
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tokens test-inputs/input.bad-cmnts
# 	# antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tree test-inputs/input.cmnts

# prog:
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tokens test-inputs/input.prog
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tree test-inputs/input.prog

# code:
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 lata -tokens test-inputs/input.code
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 lata -tree test-inputs/input.code

# lines:
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tokens test-inputs/input.lines
# 	antlr4-parse NowebParser.g4 NowebLexer.g4 prog -tree test-inputs/input.lines

# help:
# 	java -Xmx500M -cp "${JAR}:${CLASSPATH}" org.antlr.v4.Tool

