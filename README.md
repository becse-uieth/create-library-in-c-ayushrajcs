# Libraries-in-c
Here, libcalculator.a and libcalculator.so are library files created with functions of addition, subtraction, multiplication and division.
libcalculator.a is static library and libcalculator.so is shared library.

# Using static library
Download the main.c and libcalculator.a files.
compile using gcc as: gcc -I/(path of libcalculator.a) -c main.c -lcalculator

# Using Shared library
Download the main.c and libcalculator.so files.
Copy the libcalculator.so to default library directory.
compile using gcc as: gcc -c main.c -lcalculator
