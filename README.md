
#include <stdio.h>

int main(void)
{
    int i;
    double d;


   printf("Enter one Integer");
   scanf("%d", &i);
   printf("You entered %d\n\n", i);

  printf("Enter one fraction vaule");
  scanf("%lf", &d);
  printf("You entered %f\n\n", d);

  printf("Enter one integer and one fraction value");
  scanf("%d%lf",&i, &d);

  printf("you entered %d and %f\n\n", i,d);


  return 0;
}
