#include <stdio.h>
#include <windows.h>
#include<conio.h>

int token = 0,tokens[50],payment_counter=0;
void delay(unsigned int value)
{
    system("Color F3");
          unsigned int count1 = 0;
          unsigned int count2 = 0;
        for (count1 = 0; count1 < value; count1++)
        {
            for (count2 = 0; count2 < count1; count2++)
           {
           }
        }
}
    const char rocket[] =
          "           ^ \n\
          /^\\\n\
          |||\n\
          |||\n\
          |||\n\
          |$|\n\
          |$|\n\
          |$|\n\
         /|$|\\\n\
        / | | \\\n\
       |  | |  |\n\
        `-\"\"\"-`\n\
";
void rocketing()
    {
          int jumpControlAtBottom = 0;
          const int someDelay = 6000;
          int shifControl = 0;
          for (jumpControlAtBottom = 0; jumpControlAtBottom < 30; ++jumpControlAtBottom) {
            printf("\n");
          }
          fputs(rocket, stdout);
         for (shifControl = 0; shifControl < 30; ++shifControl) {
            delay(someDelay);
            printf("\n");
          }
}
int main_page()
{
    int i;
    system("cls");
    system("color 0B");
    printf("\n\n\n\n\n\n\n\t\t\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2");
    printf("\n\t\t\xB2\xDB\xDB\xDB\xDB\t\t\t\t\t\t   \xDB\xDB\xDB\xDB\xB2");
    printf("\n\n\t\t\t\t <WELCOME TO GAME STORE>\t\t");
    printf("\n\t\t\t\t");
    printf("\n\t\t\xB2\xDB\xDB\xDB\xDB\t\t\t\t\t\t   \xDB\xDB\xDB\xDB\xB2");
    printf("\n\t\t\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2");
    Sleep(100);
    time_t now;
    time(&now);
    printf("\n");
    printf("\n                               %s",ctime(&now));
    printf("\n\n\n\t\t\t                 (^_^)\n\n                          ");
    for (i=0;i<36;i++)
     {
        printf("~");
     }

    printf("\n");
    printf("                          $                                  $\n");
    printf("                          $       Select any of them -       $\n");
    printf("                          $                                  $\n");
    printf("                          $       1. Choose Games :)           $\n");
    printf("                          $                                  $\n");
    printf("                          $       2. Bill Payment.           $\n");
    printf("                          $                                  $\n");
    printf("                          $       3. Exit :(                 $");
    printf("\n");
    printf("                          $                                  $\n");
    printf("                          $                                  $\n");
    printf("                          ");

    for (i=0;i<36;i++)
     {
        printf("~");
     }
    printf("\n\n\n\n                         Enter Your Choice: ");
    int n;
    scanf("%d",&n);
    return n;
}
int menu_order()
{
    int arID[10],decision,arqty[10],Bill[10],counter=0;
    work:
    system("cls");
    system("color B");
    printf("\n\t\t   [ALL AVAILABLE GAMES]\n\t\t\n");
    printf("\n\tOpen World :\n\n");
    printf("\t1. GTA Vice City ...................... 120/=\t  \n");
    printf("\t2. San Andress..........................  40/=\n");
    printf("\t3. Call Of Duty Ghost ...........................  70/=\t \n");
    printf("\t4. FIFA 21 ..........  90/=\t \n");
    printf("\t\t\t\t\t\t\t \n\n\tCOD :\n\n");
    printf("\t5. Call Of Duty MW ...................  90/=\n");
    printf("\t6. Call Of Duty Cold War ....................  65/=\n");
    printf("\n\tCar :\n\t\t\t\t\t\t\t \n");
    printf("\t7. F1 2020 ........................  65/=\t  \n");
    printf("\t8. Need For Speed ........................... 230/=\t \n");
    printf("\n\tFight :\n\n");
    printf("\t9.  WWE 2k20 ........................ 25/=\n");
    printf("\t10. UFC4   ........................ 25/=\n");
    printf("\n\n\tOrder : (Enter 0 to finish order)\n");
    for(;;)
    {
        counter++;
        printf("\t Enter Game ID: ");
        scanf("%d",&arID[counter-1]);
        if(arID[counter-1]==0)
        {
            break;
        }
        printf("\t Enter Quantity: ");
        scanf("%d",&arqty[counter-1]);
    }
    system("cls");
    printf("\n\n\n\n\n\n\n\n\n\n\t\tThanks for your order. .\n\t\tUntil then, have some selfies with friends. Enjoy!\n\n\n\n\n\t\t\t  <Enter 1 to check your bill>\n\t\t\tEnter your choice: ");

    scanf("%d",&decision);
    printf("\n\n\n\n\n\n\n\n");
    counter--;

    if(decision==1)
    {
        Bill_show(arID,arqty,counter);
    }
    else if(decision==2)
    {
       goto work;
    }
    else if(decision==3)
    {
        main();
    }
}

void Bill_show(int arID[],int arqty[],int counter)
{

    int n;
    system("cls");
    system("color B0");

    int i,sum=0;
    int costs[10]={120,40,70,90,90,65,65,230,25,25};
    char items[10][16]={"Open World","COD","Car"};
    printf("\n\nYour Bill:\n\n\n\t\tItem(s)\t\t     Quantity\t\t    Cost\n\n\n\n");

    for(i=0;i<counter;i++)
    {
        printf("\t%2d. %-16s ________\t%-5d piece(s) ____ %7d\n",i+1,items[arID[i]-1],arqty[i],arqty[i]*costs[arID[i]-1]);
        sum=sum+(costs[arID[i]-1]*arqty[i]);
    }

    printf("\n\n\n\n\t\t\t\t\t\t\t  Total = %d\n\n\n\n",sum);
    token ++;
    tokens[token]=sum;
    printf("\tYour token number is %d. Use this token while paying the bill.\n\n\n\n\n\t\t\t<enter (1) to give another order>\n\n\t\t\t<enter (2) to go to the main menu>\n\n\t\n\t\t\tEnter your choice: ",token);
    scanf("%d",&n);
    printf("\n\n\n");
    if(n==1)
    {
        menu_order();
    }
    else if(n==2)
    {
        main();
    }
}

void Bill_Payment()
{
    int k,i,cash,changer,n;
    redo:
    payment_counter++;
    system("cls");
    system("color 3F");
    printf("\n\n\n\t\t\tEnter your token number: ");
    scanf("%d",&k);
    printf("\t\t\tYour Total Bill is = %d",tokens[k]);
    work:
            printf("\n\t\t\tPay your bill: ");
            scanf("%d",&cash);
    changer = cash-tokens[k];
    if(changer == 0)
    {
        printf("\n\t\tThanks for your payment. Have a great day!\n");
    }
    else if (changer<0)
    {
        system("cls");
        printf("\n\t\t\tAmount is not sufficient. :(\n\t\tPlease pay the fair price of your bill\n");
        goto work;
    }
    else
    {
        printf("\n\n\n\t\tHere is your change : (%d - %d) = %d Tk.\n\t\t  ",cash,tokens[k],changer);

            for(i=0;i<19;i++)
            {
                printf("_");
            }
            if(changer>=1000 )
                {printf("\n\t\t1000 Tk. note(s) = %d\n",changer/1000);
                changer=changer%1000;}
            if(changer>=500 && changer<1000)
            {printf("\n\t\t 500 Tk. note(s) = %d\n",changer/500);
            changer=changer%500;}
            if(changer>=100 && changer<500)
            {printf("\n\t\t 100 Tk. note(s) = %d\n",changer/100);
            changer= changer%100;}
            if(changer>=50 && changer<100)
            {printf("\n\t\t  50 Tk. note(s) = %d\n",changer/50);
            changer=changer%50;}
             if(changer>=10 && changer<50)
            {printf("\n\t\t  10 Tk. note(s) = %d\n",changer/10);
            changer=changer%10;}
            if(changer>=5 && changer<10)
            {printf("\n\t\t   5 Tk. note(s) = %d\n",changer/5);
            changer=changer%5;}
            if(changer>=2 && changer<5)
            {printf("\n\t\t   2 Tk. note(s) = %d\n",changer/2);
            changer=changer%2;}
            if(changer>=1 && changer<2)
            {printf("\n\t\t   1 Tk. note(s) = %d\n",changer/1);
            changer=changer%1;}

            printf("\t\t  ");
            for(i=0;i<19;i++)
            {
                printf("_");
            }
    printf("\n\n\n\n\n\t\t\tThanks for your payment.\n\t\t\t    Have a great day!\n",changer);
    }
    printf("\n\n\t\t\t<Enter (1) to pay another bill.>\n\t\t\t<Enter (2) to go back main menu>\n\n\n\t\t\tEnter your choice: \t");
        scanf("%d",&n);
        if(n==2)
        {
            main();
        }
        else if(n==1)
        {
           goto redo;
        }
}

int main()
 {

    int k,j,n,d;
    k = main_page();
    rocketing();

    if(k==1)
    {
        menu_order();
    }
    else if(k==2)
    {
        Bill_Payment();
    }
    else
    {
        system("cls");
        system("color 30");
        printf("\n\n\n\n\n\t\t       \n\t\t    Game Store      \n\t\t\t\t\t-\n\n");
        printf("\n\n\n\t\t\tThis session order recieved : %d\n\n",token);
        printf("\t\t\tThis session bill paid      : %d\n\n",payment_counter);
        if(payment_counter<token)
        {printf("\t\t\t\tYet to pay          : %d\n\n\n\n\n\n",token-payment_counter);}
        else
        {
            printf("\n\n\n\n\n\n");
        }
        return 0;
    }

 }
