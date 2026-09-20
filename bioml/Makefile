.PHONY: all
all:
	mkdir -p tmp/pdfs output/pdf
	latexmk -pdf -synctex=1 -file-line-error -interaction=nonstopmode -halt-on-error -outdir=tmp/pdfs cjoshliu-resume.tex
	cp tmp/pdfs/cjoshliu-resume.pdf output/pdf/cjoshliu-resume.pdf
	cp tmp/pdfs/cjoshliu-resume.pdf cjoshliu-resume.pdf
