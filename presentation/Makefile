SRC=gravidy
all:
	@rubber --pdf $(SRC)
x:
	okular $(SRC).pdf &> /dev/null &
clean:
	@rubber --clean $(SRC)
	@rm -f *.vrb
distclean: clean
	@rubber --clean --pdf $(SRC)
