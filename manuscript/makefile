all: manuscript.tex manuscript.pdf

manuscript.tex: manuscript.md
	 pandoc --filter pandoc-citeproc -S --standalone manuscript.md --template=resources/plos_template.tex -o manuscript.tex

manuscript.pdf: manuscript.tex
	latex manuscript
	dvipdf manuscript
