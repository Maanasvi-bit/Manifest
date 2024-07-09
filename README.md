#Size of an integer
#include <stdio.h>

int main() {
    int array[5];  // Declare an array of five integers
    
    // Calculate the size of the array in bytes
    size_t array_size = sizeof(array);
    
    // Calculate the size of an integer in bytes
    size_t int_size = sizeof(int);
    
    // Print the sizes
    printf("Size of the array (5 integers): %zu bytes\n", array_size);
    printf("Size of a single integer: %zu bytes\n", int_size);
    
    return 0;
}
