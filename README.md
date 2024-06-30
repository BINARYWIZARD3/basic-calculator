# basic-calculator

#include <stdio.h>

int main() {
    // Write C code here
    char operator;
    double num1;
    double num2;
    double result;
    printf("\nenter an operator (+,-,*,/):");
    scanf("%c",&operator);
    printf("enter a number:");
    scanf("%lf",&num1);
    printf("enter a number:");
    scanf("%lf",&num2);
    switch(operator){
        case '+':
        result=num1+num2;
        printf("\nresult :%lf",result);
        break;
        case '-':
        result=num1-num2;
        printf("\nresult :%lf",result);
        break;
        case '*':
        result=num1*num2;
        printf("\nresult :%lf",result);
        break;
        case '/':
        result=num1/num2;
        printf("\nresult :%lf",result);
        break;
        default:
        printf("%c is not an valid operator",operator);
    }

    return 0;
}
