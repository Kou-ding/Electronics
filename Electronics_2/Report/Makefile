TEX_MAIN = main.tex

all: main

main: $(TEX_MAIN)
	latexmk -pdf $(TEX_MAIN)

clean:
	latexmk -C $(TEX_MAIN)
	rm -f *.aux *.log *.out *.toc *.bbl *.blg *.fls *.fdb_latexmk