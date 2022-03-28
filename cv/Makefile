
all: release

release: cv coverletter clean-temp

coverletter: coverletter.pdf 

cv: cv.pdf 

%.pdf: %.tex
	lualatex $<

clean: clean-temp
	rm -f *.pdf *.dvi *.synctex.gz

clean-temp:
	rm -f *.log *.toc *.aux *.bbl *.blg *.bcf *.run.xml *.out *.fdb_latexmk *.fls *.nav *.snm
