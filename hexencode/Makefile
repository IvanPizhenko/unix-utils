EXE:=hexencode
SRC:=hexencode.c
OBJ:=hexencode.o
DEP:=hexencode.d

CC:=c99
CFLAGS:=-O2 -fno-omit-stack-frames

LD:=$(CC)

all: $(EXE)

clean:
	-rm -rf $(EXE) $(OBJ) $(DEP)

$(EXE): $(OBJ)
    $(LD) $(LDFLAGS) $(OBJ) -o $(EXE)
