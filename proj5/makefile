NAME=proj5

all:
	pdflatex $(NAME).tex $^
	bibtex $(NAME).aux $^
	pdflatex $(NAME).tex $^
	dvips -t a4 $(NAME).dvi $^
	ps2pdf $(NAME).ps x $^
	pdflatex $(NAME).tex $^
	bibtex $(NAME).aux $^
	pdflatex $(NAME).tex $^
	dvips -t a4 $(NAME).dvi $^
	ps2pdf $(NAME).ps x $^
	pdflatex $(NAME).tex $^
