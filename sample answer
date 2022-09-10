#include<stdio.h>
#include<stdlib.h>
#pragma warning(disable:4996)


void main() {
	char fName[21];
	char yesOrNo;
	float price, amount, tax;
	const float TAX_RATE = 0.06;
	int bill=1;

	do {
		printf("Please enter a food name: ");
		rewind(stdin);
		scanf("%[^\n]", fName);
		printf("\nThe price of the food : RM ");
		scanf("%f", &price);

		tax = price * TAX_RATE;
		amount = tax + price;
		printf("\nBill No : %d", bill);
		printf("\n====================================================\n");
		printf("Food Name :                         %s\n", fName);
		printf("The price of the food :             RM %.2f\n", price);
		printf("Tax Rate :                          6%%");
		printf("\n====================================================\n");
		printf("The tax price :                     RM %.2f", tax);
		printf("\nTotal amount to pay :               RM %.2f", amount);
		printf("\n\n");

		printf("\nNext Order? (Yes press 'Y' or No press 'N') > ");
		rewind(stdin);
		scanf("%c", &yesOrNo);

		if (yesOrNo == 'Y' || yesOrNo=='y') {
			bill++;
		}
		printf("\n\n");
	} while (yesOrNo == 'Y' || yesOrNo =='y');


	system("pause");
}
