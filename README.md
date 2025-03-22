#include <stdio.h>
#include <math.h>

int main() {
  double num;

  printf("Enter a number: ");
  scanf("%lf", &num);

  // Check if the number is whole
  if (num == floor(num)) {
    printf("%.2lf is a whole number.\n", num);
  } else {
    printf("%.2lf is not a whole number.\n", num);
  }

  return 0;
}
