#include <stdio.h>
#include <conio.h>
main()
{

	int a,b,c,d,e,f;
a1:	printf(" Please select the program menu\n");
	printf("Choose 1 Program Find Area of a Triangle \n");
	printf("Choose 2 Program Find Area of a Quaree \n");
	printf("Choose 3 Exit Program \n");
	scanf("%d",&a);
	switch(a)
	{
		case(1):
			{
				printf("Program Find Area of a Triangle");
				printf("\nEnter long = ");
				scanf("%d",&b);
				printf("\nEnter base = ");
				scanf("%d",&c);
				f=0.5*b*c;
				printf("\narea of Triangle = %d",f);
				break;
			}
		case(2):
			{
				printf("Program Find Area of a Quaree");
				printf("\nEnter long = ");
				scanf("d",&d);
				printf("\nEnter wide = ");
				scanf("%d",&e);
				printf("\narea of Quaree = %d",d*e);
				break;
			}
		case(3):
			{
				printf("\nExit Program");
				break;
			}
			default:
				{
					printf("Please select the program again");
					goto a1;
				}
	}
	getch();
}
