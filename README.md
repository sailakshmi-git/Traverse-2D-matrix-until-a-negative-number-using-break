# Traverse-2D-matrix-until-a-negative-number-using-break
Write a C program to traverse a 2D matrix and print the values until a negative number is found. Use break statement.

Program:

```
#include <stdio.h>

int main() {
    int arr[3][3] = {
        {1, 2, 3},
        {4, -5, 6},
        {7, 8, 9}
    };

    for(int i = 0; i < 3; i++) {
        for(int j = 0; j < 3; j++) {
            if(arr[i][j] < 0) {
                printf("Negative number found. Stopping...\n");
                break;
            }
            printf("%d ", arr[i][j]);
        }
        printf("\n");
    }

    return 0;
}
```

Output:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bcdb004a-0c7e-499e-af37-b0efe0f0d234" />
