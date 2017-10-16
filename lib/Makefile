.PHONY : clean
CC = gcc
CFLAGS = -g -I
OUTPUT = libfuncs.a
OBJFILES = func1.o func2.o
INCLUDE = /home/kimky/embedded_sw/include

$(OUTPUT) : $(OBJFILES)
	ar rv $(OUTPUT) $(OBJFILES)
%.o : %.c
	$(CC) $(CFLAGS)$(INCLUDE) -c $< -o $@
clean:
	rm *.o $(OUTPUT)
