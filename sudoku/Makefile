# compiler
CC:=g++

# where and what type are output
OUTPUTDIR:=output/
OUTPUT:=$(OUTPUTDIR)*.txt

# where are source files
SRC_FILES:=src/$(PROGNAME).cpp

# create runable program
sudoku: $(SRC_FILES)
	$(CC) $^ -o $@
	
# remove previous results
purge: 
	-rm -f sudoku $(OUTPUT)

run_sudoku: purge sudoku
	./sudoku