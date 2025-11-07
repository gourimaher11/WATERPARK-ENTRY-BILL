# WATERPARK-ENTRY-BILL


#include<stdio.h>
int main()
{
    printf("*FUN N FOOD*");
	printf("\n==================================================");
   char name[30];
    printf("\nName:");
    scanf("%s",&name );
 
int Id;
    printf("\n\nId: ");
    scanf("%d",&Id);
	
int Telephone;
 
	printf ("\n\nTelephone:");
    scanf("%d",&Telephone);
	
	int Day,Month,Year;
    printf("\n\nDate(DD/MM/YYYY): ");
    scanf("%d/%d/%d",&Day,&Month,&Year);
	
	int age;
    printf("\n\n Enter your age:    "  );
    scanf("%d",&age);
if ( age <=18)
{
printf("\nYou are underage\nEntry fees=200");
}
else
{
    printf("\nYou are an adult\nEntry fees=500\n");
}
 
return 0;
}
