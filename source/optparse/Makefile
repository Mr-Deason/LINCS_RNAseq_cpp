main : main.o optparse.o

main.o : main.c optparse.h
optparse.o : optparse.c optparse.h

run : main
	./$^ -abdfoo -c bar subcommand example.txt -a

clean :
	$(RM) test *.o
