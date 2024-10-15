

```c
#include <stdio.h>
int main() {
    int a, b, sum;
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);
    sum = a + b;
    printf("The sum is: %d\n", sum);
    return 0;
}
```

2. 

```c
#include <stdio.h>
int main() {
    int num, square;
    printf("Enter an integer: ");
    scanf("%d", &num);
    square = num * num;
    printf("The square is: %d\n", square);
    return 0;
}
```

3.  its equivalent in Fahrenheit:

```c
#include <stdio.h>
int main() {
    float celsius, fahrenheit;
    printf("Enter temperature in Celsius: ");
    scanf("%f", &celsius);
    fahrenheit = (celsius * 9 / 5) + 32;
    printf("Temperature in Fahrenheit: %.2f\n", fahrenheit);
    return 0;
}
```

4.  its equivalent in Celsius:

```c
#include <stdio.h>
int main() {
    float fahrenheit, celsius;
    printf("Enter temperature in Fahrenheit: ");
    scanf("%f", &fahrenheit);
    celsius = (fahrenheit - 32) * 5 / 9;
    printf("Temperature in Celsius: %.2f\n", celsius);
    return 0;
}
```

.
