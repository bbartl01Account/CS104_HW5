objects = main.o addition.o subtraction.o multiplication.o division.o

## Create the binary file
calculator: $(objects)
	cc -o calculator $(objects)

## Create Object Files
$(objects): operations.h

clean:
	cc -o calculator $(objects)
	rm -f $(objects)
