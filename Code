#include <stdio.h>
#include <stdlib.h>
struct details
{
    char name[20];
    int age;
    char gender;
};

struct price
{
     int food;
     int blanket;
     int coach;
};

void view_ticket(int num, struct details ticket[10], int meal, int train);
int main()
{
    int num, i;
    struct details ticket[20];
    int train;
    printf("TRAIN NO  SN0.   TRAIN NAME       FROM             TO              PRICE\n");
    printf("__________\n");
    printf("22123     1      MUMBAI EXP       MUM(3:00)       DEL(23:59)       2200\n");
    printf("28964     2      BARELI EXP       BAR(8:00)       BUJH(22:59)      1500\n");
    printf("26934     3      AHMDEBAD EXP     AHM(22:53)      BAR(9:00)        3000\n");
    printf("20999     4      RAJDHANI EXP     MUM(18:50)      GOA(11:00)       1800\n");
    printf("23339     5      JAIPUR EXP       JAI(13:00)      KAN(5:00)        2400\n\n");
    printf("Choose your desired train from the list(input Sno.)\n");
    scanf("%d", &train);
    printf("Enter the number of people: ");
    scanf("%d", &num);
    for (i=0; i<num; i++)
    {
        printf("Enter details of passenger %d -(in form of name age gender) : ", i+1);
        scanf("%s %d %c",&ticket[i].name,&ticket[i].age,&ticket[i].gender);
    }
    struct price a;
    int x, tp;
    if(train==1)
    {
        printf("Extra price for AC as follows =\n 1-First class AC = 1500 \n 2-Second class AC=1200\n 3-Third class Ac = 1000\n 4-Non AC->(No extra charges) \n Enter your choice in form of 1,2,3 or 4\n ");
        scanf("%d", &a.coach);
        if(a.coach==1)
        {
            x=(1500 +2200)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==2)
        {
            x=(1200+2200)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==3)
        {
            x=(1000+2200)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==4)
        {
            x=2200*num;
        }
    }
    if(train==2)
    {
        printf("Extra price for AC as follows =\n 1-First class AC=1500 \n 2-Second class AC = 1200\n 3-Third class AC = 1000\n 4-Non AC->(No extra charges)\n Enter your choice in form of 1,2,3 or 4\n ");
        ("%d",&a.coach);
        if(a.coach==1)
        {
            x=(1500 +1500)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==2)
        {
            x=(1200+1500)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==3)
        {
            x=(1000+1500)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==4)
        {
            x=1500*num;
        }
    }
    if(train==3)
    {
        printf("Extra price for AC as follows =\n 1-First class AC=1500 \n 2-Second class AC = 1200\n 3-Third class AC = 1000\n 4-Non AC->(No extra charges)\n Enter your choice in form of 1,2,3 or 4\n ");
        scanf("%d", &a.coach);
        if(a.coach==1)
        {
            x=(1500 +3000)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==2)
        {
            x=(1200+3000)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==3)
        {
            x=(1000+3000)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==4)
        {
            x=3000*num;
        }
    }
    if(train==4)
    {
        printf("Extra price for AC as follows =\n 1-First class ac=1500 \n 2-Second class AC = 1200\n 3-Third class AC = 1000\n 4-Non AC->(No extra charges)\n Enter your choice in form of 1,2,3 or 4\n ");
        scanf("%d",&a.coach);
        if(a.coach==1)
        {
            x=(1500 +1800)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==2)
        {
            x=(1200+1800)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==3)
        {
            x=(1000+1800)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==4)
        {
            x=1800*num;
        }
    }
    if(train==5)
    {
        printf("Extra price for AC as follows =\n 1-First class AC = 1500 \n 2-Second class AC = 1200\n 3-Third class AC = 1000\n 4-Non AC->(No extra charges)\n Enter your choice in form of 1,2,3 or 4\n ");
        scanf("%d",&a.coach);
        if(a.coach==1)
        {
            x=(1500 +2400)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==2)
        {
            x=(1200+2400)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==3)
        {
            x=(1000+2400)*num;
            printf("Total price is equal to=%d\n",x);
        }
        else if(a.coach==4)
        {
            x=2400*num;
        }
    }
    printf("Enter the number of blankets with pillows required(each set landed will cost 300 rupees)\n");
    scanf("%d",&a.blanket);
    printf("Enter the number of food servings required (each serving costs 120 rupees)\n");
    scanf("%d",&a.food);
    int meal;
    printf("Choose meal 1 for Non-Veg and 2-Veg\n");
    scanf("%d",&meal);
    switch (meal)
    {
        case 1:
            printf("NON VEG. ONE meal costs rs 150\n");
            tp= x + 150*a.food+ 300*a.blanket;
            printf("The total cost is equal to =%d\n",tp);
            break;
        case 2:
            printf("VEG. ONE meal costs rs 120\n");
            tp= x + 120*a.food+ 300*a.blanket;
            printf("The total cost is equal to =%d\n",tp);
            break;
        default:
            tp = x;
            printf("The total cost is equal to = %d", tp);
    }
    view_ticket(num, ticket, meal, train);
    return 0;
}
void view_ticket(int n, struct details ticket[10], int meal, int train)
{
    int w,i;
    printf("Press 1 to view ticket.\nPress 0 to exit.");
    scanf("%d", &w);
    switch(w)
    {
        case 1:
            for(i=0;i<n;i++)
            {
                printf("Passenger %d Details :- \n\n", i+1);
                printf("Passenger Name: %s\n\n",ticket[i].name);
                printf("Passenger Age: %d\n\n",ticket[i].age);
                printf("Passenger Gender: %c\n\n",ticket[i].gender);
            }
            switch(train)
            {
                case 1:
                    printf("22123     1      MUMBAI EXP       MUM(3:00)       DEL(23:59)       2200\n");
                    break;
                case 2:
                    printf("28964     2      BARELI EXP       BAR(8:00)       BUJH(22:59)      1500\n");
                    break;
                case 3:
                    printf("26934     3      AHMDEBAD EXP     AHM(22:53)      BAR(9:00)        3000\n");
                    break;
                case 4:
                    printf("20999     4      RAJDHANI EXP     MUM(18:50)      GOA(11:00)       1800\n");
                    break;
                case 5:
                    printf("23339     5      JAIPUR EXP       JAI(13:00)      KAN(5:00)        2400\n\n");
                    break;
            }
            if(meal==1) {
                printf("\nTicket price includes non-veg meal.");
            }
            else if (meal==2) {
                printf("\nTicket price includes veg meal.");
            }
            break;
        case 2:
            exit(0);
    }
}
