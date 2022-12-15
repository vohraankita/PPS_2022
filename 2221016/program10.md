## Program 31: Write a program to perform linear search
```c 
#include <stdio.h>
int main(){
    int len,target,ind;
    printf("Enter size of array\n");
    scanf("%d",&len);
    int arr[len];
    printf("Enter elements:\n");
    for(int i=0;i<len;i++){
        printf("Enter element at index %d -> ",i);
        scanf("%d",&arr[i]);
    }
    printf("Enter element to search -> ");
    scanf("%d",&target);
    printf("\nEntered array is :\n");
    for(int i=0;i<len;i++){
        printf("%d\t",arr[i]);
    }
    printf("\n");
    for(int i=0;i<len;i++){
        if(arr[i] == target)ind=i;
    }
    printf("\nLocation of %d in array = %d\n",target,ind);
}
```
### Output:
```
Enter size of array
10
Enter elements:
Enter element at index 0 -> 43
Enter element at index 1 -> 65
Enter element at index 2 -> 786
Enter element at index 3 -> 12
Enter element at index 4 -> 54
Enter element at index 5 -> 75
Enter element at index 6 -> 32
Enter element at index 7 -> 7
Enter element at index 8 -> 21
Enter element at index 9 -> 5
Enter element to search -> 7
Entered array is :
43	65	786	12	54	75	32	7	21	5	
Location of 7 in array = 7
```
