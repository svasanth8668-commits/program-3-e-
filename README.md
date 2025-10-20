# program-3-e-
C module 3


EX NO:3-e) Count the number of Odd and Even elements in an array. 

Date:19/10/2025 

Name: VASANTH S 

Ref no: 25017538

AIM:
To write a C program to count the number if odd and even elemets in an array.

ALGORITHM:
1) Get an array as input from the user.
2) Count the number of odd and even elements by using for loop and if else statements.
3) Print the number of odd and even elements  using printf() function.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int num,odd=0,even=0;
    scanf("%d",&num);
    int arr[num];
    for(int i=0;i<num;i++)
    {
        scanf("%d",&arr[i]);
    }
    for(int j=0;j<num;j++)
    {
        if(arr[j]%2==0)
        even++;
        else
        odd++;
        
    }
    printf("Total even elements: %d\n",even);
    printf("Total odd elements: %d",odd); 
}
```
OUTPUT:
<img width="773" height="126" alt="Screenshot 2025-10-20 110415" src="https://github.com/user-attachments/assets/02888641-2331-4312-95c0-385611fc323c" />

RESULT:
Thus the C program to count the number of odd and even elements in a given array is executed successfully.







