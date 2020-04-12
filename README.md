# menu
To give the food item based on required selection
#include<stdio.h> 
int main()
{
int x;
printf("Enter the choice\n");
scanf("%d",&x);
switch(x)
{
case 1:
printf("Food item - Burger\nPrice - Rs 129\n");
break;
case 2:
printf("Food item - Pizza\nPrice - Rs 239\n");
break; 
case 3:
printf("Food item- Pasta\n Price - Rs 179\n");
break;
case 4:
printf("Food item- Sandwich\nPrice - Rs 149\n"); 
break;
case 5:
printf("Food item- French Fries\nPrice - Rs 99\n");
break;
default:
printf("Wrong choice \n");
break;
}
return 0;
}


