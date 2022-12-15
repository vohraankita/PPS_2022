## Program 22 : Write a program using string copy function.
```C
#include<stdio.h>
#include<string.h>
int main()
{
char a[]="I am a student of";
char b[]="Guru Nanak Dev Engineering";
strcpy(b,a);
printf("%s",a);
printf("\n%s",b);
return 0;
}
```
**Output :**
```
I am a student of
I am a student of
