.PHONY = clean
INCLUDE = /home/kimky/embedded_sw/include
LIB = /home/kimky/embedded_sw/lib

CC = gcc
CFLAGS = -g -c -I
OUTPUT = main
OBJFILES = main.o

$(OUTPUT) : $(OBJFILES)
	$(CC) -o $(OUTPUT) -L $(LIB) $(OBJFILES) -lfuncs
%.o : %.c
	$(CC) $(CFLAGS)$(INCLUDE) -c $< -o $@
clean:
	rm *.o main
