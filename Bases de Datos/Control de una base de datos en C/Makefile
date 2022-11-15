programa1.out: mysql.o
	gcc -o programa.out mysql.o -lmysqlclient -lnsl -lm -lz

mysql.o: mysql.c
	gcc -c mysql.c

clean:
	rm *.o
