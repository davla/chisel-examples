MAIN?=make_same

all:
	patmos-clang -O2 $(MAIN).c -I ../.. -I ../../include ../../libcorethread/*.c -o $(APP).elf

clean:
	rm *.elf
