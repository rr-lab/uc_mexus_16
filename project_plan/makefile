all: uc_mexus_2016_rellan_fiehn.pdf
uc_mexus_2016_rellan_fiehn.pdf: uc_mexus_2016_rellan_fiehn.md biblio_uc_mexus.bib
	pandoc -V geometry:margin=1.5in -H format.sty --latex-engine=xelatex --bibliography biblio_uc_mexus.bib --csl=nature.csl uc_mexus_2016_rellan_fiehn.md -o uc_mexus_2016_rellan_fiehn.pdf
