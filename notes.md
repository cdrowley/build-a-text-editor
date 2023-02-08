# check C compiler version
cc --version

# check make version
make -v

# a c program
echo "int main() {return 0;}" >> kilo.c

# compile a C program
cc -o kilo kilo.c

# run the compiled program
./kilo

# check the exit status of the last command
echo $?