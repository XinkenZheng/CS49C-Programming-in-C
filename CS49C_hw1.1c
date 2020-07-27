//the following code will convert a binary number to a decimal number;
#include <stdio.h>
#include <math.h>

int main(void) {
  printf("Enter a binary number");
  int num;
  scanf("%d", &num);

  int power=0;  //power increase by LSB to MSB
  int decimal; //calculating decimal number by bit
  int total;  //adding the decimal value to total

  while(num > 0)
  {
    decimal = (num%10) * pow(2,power); //Decimal value of the LSB bit
    total = total + decimal;
    num = num / 10;
    power = power+1;  //move to next bit, power +1;
  }

  printf("%d", total);
}

/*

Enter a binary number1010
10

Enter a binary number1111
15

Enter a binary number101010110
342

Enter a binary number00000111
7

*/
