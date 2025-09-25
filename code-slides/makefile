# Nom du fichier source (sans extension)
MAIN=delay_et_al

all: $(MAIN).pdf

$(MAIN).pdf: $(MAIN).tex
	pdflatex $(MAIN).tex
	pdflatex $(MAIN).tex

clean:
	rm -f *.aux *.log *.out *.toc *.lof *.lot *.fls *.fdb_latexmk

mrproper: clean
	rm -f $(MAIN).pdf
