TARGET=calculator
sFile = addition.c division.c main.c multiplication.c subtraction.c
OBJS = $(sFile:.c=.o)

all:$(TARGET)

$(TARGET): $(OBJS)
	cc -o $(TARGET) $(OBJS)

%.0: %.c operations.h
	cc -c $< -o $@

clean:
	rm -f $(TARGET) $(OBJS)

