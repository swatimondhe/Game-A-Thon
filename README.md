# Game-A-Thon
## Name-Swati Madhusudan Mondhe

### Problem Statement 1:Write a code to multiply two integer
```c
#include <stdio.h>
int main() {
  int n, i;
  printf("Enter an integer: ");
  scanf("%d", &n);
  for (i = 1; i <= 10; ++i) {
    printf("%d * %d = %d \n", n, i, n * i);
  }
  return 0;
}
```
### Problem Statement 2:Write a code to sum of two digit
```c
#include <stdio.h>
int main() {    

    int a, b, sum;
    
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);

   
    sum = a + b;      
    
    printf("%d + %d = %d", a, b, sum);
    return 0;
}
```
