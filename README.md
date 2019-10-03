#include<stdio.h>
int main()
{
	int price;
  float discount, True_Price;
	printf("Input Price = ");
	scanf("%d",&price);
	printf("Input Discount = ");
	scanf("%f",&discount);
	True_Price = price - (price*discount/100);
	printf ("True Price is %.2f",True_Price);
	return 0;
}
