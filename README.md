# C-LANGUAGE {LEARNING}
1) HOW TO TYE HELLO WORLD
#include<stdio.h>
int main(){
printf("hello world");
return 0;
RESULTE= HELLO WORLD


2) how to find area of rectangle:
#include<stdio.h>
int main(){
    int length,breadth;
    printf("enter length\n");
    scanf("%d",&length);
    printf("enter breadth\n");
    scanf("%d",&breadth);
    printf("the area of rectangle is %d",length*breadth);
}

3) HOW TO CONVET CELSIUS TO FAHRENHEIT :
#include<stdio.h>
int main(){
    float c=33.0,f;
    f=((9.0/5.0)*c)+32;
    printf("%f",f);
    return 0;
}

4) HOW TO CONVERT FAHRENHEIT TO CELSIOUS :
   #include<stdio.h>
int main(){
    float f=91.4,c;
    c=((f-32)/9)*5;
    printf("%f",c);
    return 0;
}

5) HOW TO FIND SIMPAL INTREST :{FOR INPUT} :
#include<stdio.h>
int main(){
    float p=34.5;
    int r=4;
    int t=5;
    printf("the vale of simpal interest is %f",p*r*t/100);
    return 0;
}

6) HOW TO FINT SIMPAL INTREST {FOR OUTPUT} :
   
#include<stdio.h>
int main(){
    float p,r,t,si;
    printf("enter the principal amount p");
    scanf("%f",&p);
     printf("enter the ratr of intrest r");
    scanf("%f",&r);
     printf("enter the time of interst t");
    scanf("%f",&t);
    si =p*r*t/100;
    printf("simpale intrest is %.2f\n",si);

    return 0;

}



