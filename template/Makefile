TARGET=main

all: release

release: pdf clean-temp

pdf: $(TARGET).pdf 

%.pdf: %.tex
	lualatex $<


clean: clean-temp
	rm -f *.pdf *.dvi *.synctex.gz

clean-temp:
	rm -f *.log *.toc *.aux *.bbl *.blg *.bcf *.run.xml *.out *.fdb_latexmk *.fls *.nav *.snm
