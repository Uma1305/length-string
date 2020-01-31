#include<stdio.h>
int main()
{
    char str[20];
    int count=0,i;
    printf("enter the string:");
    scanf("%s",str);
 //gets(str);
 printf("%s",str);
 //puts(str);
 for(i=0;str[i]!='\0';i++)
 {
     count++;
 }
 printf("length:%d",count);
}
output:
enter the string:umasiva
7
