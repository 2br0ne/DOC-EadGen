all: document/soutenanceDoc.pdf

document/soutenanceDoc.pdf: slides/soutenanceDoc.tex
	pdflatex -output-directory document/ slides/soutenanceDoc.tex
	pdflatex -output-directory document/ slides/soutenanceDoc.tex
	rm document/*.toc document/*.out document/*.aux document/*.cb document/*.cb2 document/*.log 

clean: 
	rm document/*
