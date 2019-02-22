all: aboutme 
target=MarcLijour-About-me

aboutme:
	pdflatex -output-directory=.. ${target}

view:
	xreader ${target3}.pdf &

clean: 
	@rm -f *.aux *~ *.log *.out *.backup *.bak ../*.aux ../*.log ../*~ ../*.out ../*.bak ../*.backup

