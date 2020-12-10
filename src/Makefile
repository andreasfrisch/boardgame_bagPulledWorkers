All: moveassets clean

villageTokens:
	./latexdockercmd.sh pdflatex village_tokens.tex

tiles:
	./latexdockercmd.sh pdflatex tiles.tex

playerTokens:
	./latexdockercmd.sh pdflatex player_tokens.tex

playerBoards:
	./latexdockercmd.sh pdflatex player_boards.tex

stateBoard:
	./latexdockercmd.sh pdflatex state_board.tex

churchBoard:
	./latexdockercmd.sh pdflatex church_board.tex

moveassets: tiles playerTokens playerBoards villageTokens stateBoard churchBoard
	mv tiles.pdf ../
	mv player_tokens.pdf ../
	mv village_tokens.pdf ../
	mv player_boards.pdf ../
	mv state_board.pdf ../
	mv church_board.pdf ../

clean:
	rm *.log *.aux
