# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:25/03/2026
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start.
2. Declare a array size value of type int.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Initialize array elements.
6. Replace all even elements to E
7. End.  

## Program:
```
#include <stdio.h>
int main() {
 int arr[100], n;
 scanf("%d", &n);
 for (int i = 0; i < n; i++) {
 scanf("%d", &arr[i]);
 }
 for (int i = 0; i < n; i++) {
 if (arr[i] % 2 == 0)
 printf("E ");
 else
 printf("%d ", arr[i]);
 }
 printf("\n");
 return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/e8c77e2e-c749-46b8-a664-45d58e4dc52f)


## Result:
Thus the program was executed and the output was verified successfully.
