objects = main.o kbd.o
# objects = *.o
edit : $(objects)
	cc -o edit $(objects)
# $(objects) : kbd.h
# main.o : kbd.h
#kbd.o : kbd.h
#	cc -c kbd.c
# all : main.o kbd.o
# .PHONY : all

%.o : %.c %.h
	$(CC) -c $< -o $@

.PHONY : clean
clean : 
# -rm edit $(objects)
	-rm edit *.o
