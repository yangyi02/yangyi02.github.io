NAME = cv

$(NAME).pdf : *.tex
	-pdflatex $(NAME).tex
	-rm -rf $(NAME).log

clean: 
	-rm -rf $(NAME).pdf $(NAME).log

show:
	-evince $(NAME).pdf
