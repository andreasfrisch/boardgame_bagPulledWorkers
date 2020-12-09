All: moveassets clean

tiles:
	./latexdockercmd.sh pdflatex tiles.tex

playerTokens:
	./latexdockercmd.sh pdflatex player_tokens.tex

moveassets: tiles playerTokens
	mv tiles.pdf ../
	mv player_tokens.pdf ../

clean:
	rm *.log *.aux
