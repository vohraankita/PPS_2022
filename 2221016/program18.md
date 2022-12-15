## Program 24 : Write a program using string comparison function.
```C
#include<stdio.h>
#include<string.h>
int main()
{
    char a1[]="I am a student of";
    char a2[]=" Guru Nanak Dev Engineering College";
    if(strcmp(a1,a2)==0)
    {
    printf("String 1 and String 2 are equal");
    }
    else
{
printf("String 1 and String 2 are not equal");
}
return 0;
}
```
**Output :**
```
String 1 and String 2 are not equal
