SRC := outline


hellomake:
	pdflatex $(SRC)
	bibtex $(SRC)
	pdflatex $(SRC)
	pdflatex $(SRC)

clean:
	rm $(SRC).aux $(SRC).bbl $(SRC).blg $(SRC).log $(SRC).out