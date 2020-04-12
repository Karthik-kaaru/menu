# menu
To give the food item based on required selection
#include<studio.h>
void main()
{
 int x;
 printf("Enter the choice\n");
 scanf("%d",&x);
 switch(x)
 {
  Case 1:
  printf("Food item- Burger\n
          Price - Rs 129\n");
  break;
  Case 2:
   printf("Food item- Pizza\n
          Price - Rs 239 \n");
  break; 
  Case 3:
  printf("Food item- Pasta\n
          Price - Rs 179\n");
  break; 
  Case 4:
  printf("Food item- Sandwich\n
          Price - Rs 149\n");
  break;
  Case 5:
  printf("Food item- French Fries \n
          Price - Rs 99\n");
  break;
  default:
  printf("Wrong choice \n");
  break;
}
return 0;
}

