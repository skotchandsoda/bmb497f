SRC = prog.c
BIN = prog

all: $(BIN)

$(BIN): $(SRC)
	$(CC) -o $@ $<

.PHONY: clean
clean:
	rm -rf $(BIN)
