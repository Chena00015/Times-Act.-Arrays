#include<stdio.h>


int main()
{
    int uid [3][2]={{1515,5151}, 
                   {2211,1122}, 
                   {1357,9753}};
    int user, pin;

printf("Enter ID number: ");
scanf("%d", &user);
printf("Enter PIN: ");
scanf("%d",&pin);

 if(user == uid [0][0] && pin== uid [0][1]) {
        printf("\nYou have successfully logged in\n");
        printf("ID# : %d\n", uid[0][0]);
    } else if (user == uid[1][0] && pin == uid[1][1]) {
        printf("\nYou have successfully logged in\n");
        printf("ID# : %d\n", uid[1][0]);
    } else if (user == uid[2][0] && pin == uid[2][1]) {
        printf("\nYou have successfully logged in\n");
        printf("ID# : %d\n", uid[2][0]);
    } else { printf("\n Invalid ID/PIN! \n"); }
    
return 0;
}
