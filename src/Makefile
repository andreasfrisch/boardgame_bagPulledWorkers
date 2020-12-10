All: moveassets clean

villageTokens:
	./latexdockercmd.sh pdflatex village_tokens.tex

tiles:
	./latexdockercmd.sh pdflatex tiles.tex

playerTokens:
	./latexdockercmd.sh pdflatex player_tokens.tex

playerBoards:
	./latexdockercmd.sh pdflatex player_boards.tex

moveassets: tiles playerTokens playerBoards villageTokens
	mv tiles.pdf ../
	mv player_tokens.pdf ../
	mv village_tokens.pdf ../
	mv player_boards.pdf ../

clean:
	rm *.log *.aux
