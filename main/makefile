SRCS  := $(wildcard *.c)
TARGET := $(SRCS:.c=)
LFLAG := -L ../lib -lapc
CFLAG := -I ../include

all : ${TARGET} 

%:%.c
	gcc  $^ ${LFLAG} ${CFLAG} -o $@

clean:
		rm ${TARGET}
