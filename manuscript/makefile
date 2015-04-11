all: manuscript.tex manuscript.pdf

.PHONY: all clean

manuscript.tex: manuscript.md
	 pandoc --filter pandoc-citeproc -S --standalone manuscript.md --template=resources/plos_template.tex -o manuscript.tex

manuscript.pdf: manuscript.tex
	latex manuscript
	dvipdf manuscript

clean:
	-@rm -f *.aux *.dvi *.log *.out *.tex
