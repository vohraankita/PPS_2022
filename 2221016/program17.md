## Program 23 : Write a program using string concatenate function.
```C
#include<stdio.h>
#include<string.h>
int main()
{
    char a[]="I am a student of";
    char b[]=" Guru Nanak Dev Engineering College";
    strcat(a,b);
    printf("%s",a);
    return 0;
}
```
**Output :**
```
I am a student of Guru Nanak Dev Engineering College
