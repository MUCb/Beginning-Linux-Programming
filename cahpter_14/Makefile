all: shm1 shm2

shm1: shm1.c shm_com.h
	gcc -Wall -pedantic -std=c99 shm1.c -D_XOPEN_SOURCE=700 -o shm1.out

shm2: shm2.c shm_com.h
	gcc -Wall -pedantic -std=c99 shm2.c -D_XOPEN_SOURCE=700 -o shm2.out

