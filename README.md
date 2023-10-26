# programme based on if and elseif statement 
 real life problem based programme and also the struggle of middle class boy for marriage to a girl
#include<stdio.h>
int main()
{
    int jobs;
    printf("1. person is CEO\n" "2.person is bankmanager\n" "3. person is GovermentPion\n");
    printf("choose the options from the above given jobs\n");
    scanf("%d" , &jobs);

    if(jobs == 1){

        printf("the father of girl will not be ready for marriage of her daughter from that person ! \n");

    
    }

    else if (jobs == 2){

        printf("the father of girl will not be ready for marriage of her daughter from that person ! \n");


    }

    else if (jobs == 3){

        printf("the father of girl will always be ready for marriage of her daughter from you ! \n");
    }
    
    switch (jobs)
    {
    case 1:
        
        printf("According to society you are great and welthiest person ! \n");

        printf("but still you can't do marriage easily ! \n");
        
        printf("you have to do struggle to marriage from a girl ! \n");

        printf("cause you  have not a goverment job ! \n");
        break;
    
    case 2:
        
        printf("According to you , you did your job perfectly and enough rich to manage your house ! \n");

    default:

        printf("you just earn 4,00,000 rupees for a year only but the above earn more than you , casue of your goverment job father of girl want to marriage of her daughter from you ! \n");

        printf("Shame on you ! \n");

        printf("You only take advantage of your goverment job ! \n");


        break;


    }

    return 0;
    


    

}