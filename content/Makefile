all: html pdf

html einsteiger.html: *.asciidoc Makefile
	asciidoc -a toc -a toclevels=3 einsteiger.asciidoc

pdf einsteiger.pdf: *.asciidoc Makefile
	a2x -L -f pdf einsteiger.asciidoc
