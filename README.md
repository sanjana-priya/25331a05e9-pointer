#include <stdio.h>

int main() {
printf("25331A05E9\n");
    
    int arr[] = {10, 20, 30, 40, 50};
    
    
    int *ptr = arr; 
    
    
    int n = sizeof(arr) / sizeof(arr[0]);

    printf("Accessing array elements using pointers:\n");

    
    for (int i = 0; i < n; i++) {
        // *(ptr + i) is equivalent to arr[i]
        printf("Element at index %d: %d\n", i, *(ptr + i));
    }

    return 0;
}
