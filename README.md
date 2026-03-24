# C-Module-4
# Program 1:
## AIM: 
To write a C program to do left shift and right shift operation.  
## ALGORITHM:
```
1) Get a number as a input from the user. 
2) Use left shift and right shift operators to do left and right shift operations. 
3) Use printf() function to print the output. 
```
## PROGRAM: 
``` 
#include <stdio.h> 
int main() { 
    unsigned int a=22 ; /* 60 = 0011 1100 */   
      int c = 0;  
    c = a << 2;     /* 240 = 1111 0000 */ 
   printf("After Left Shift Operation value of a is:%d\n", c ); 
   c = a >> 2;     /* 15 = 0000 1111 */ 
   printf("After Right Shift Operation value of a is:%d\n", c ); 
} 
``` 
## OUTPUT: 
<img width="980" height="126" alt="Screenshot 2025-10-20 131504" 
src="https://github.com/user-attachments/assets/65555570-3725-4c51-a68c-aa69d681f8ef" 
/> 
## RESULT: 
Thus the C program to do left shift and right shift operations is successfully executed. 
# Program  2:
## AIM: 
To write a C program to check whether the given number is positive, negative or zero using 
simple if else statements.  
## ALGORITHM: 
```
1) Get a number as an input from the user. 
2) Check whether the given number is positive, negative or zero using if else statements. 
3) Print the result using printf() function. 
``` 
## PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
    int num; 
    scanf("%d",&num); 
    if(num<0) 
    printf("Number is NEGATIVE"); 
    else if(num>0) 
    printf("Number is POSITIVE"); 
    else 
    printf("Number is ZERO"); 
} 
``` 
## OUTPUT: 
<img width="534" height="190" alt="Screenshot 2025-10-20 132434" 
src="https://github.com/user-attachments/assets/3db047d7-65ee-413e-8554-b383a652d9de
" /> 
## RESULT: 
Thus the C program to check whether the given number is positive, negative or zero is 
executed successfully. 
# Program 3: 
## AIM: 
To find the length of a given string. 
## ALGORITHM: 
1) Get a string as input from the user. 
2) find the length of the sting using strlen() function. 
3) Print the length of the string using printf() function. 
## PROGRAM: 
``` 
#include <string.h> 
# include<stdio.h> 
int main() 
{ 
char Str[1000]; 
scanf("%s", Str); 
printf("Length of Str is %ld",strlen(Str)); 
return 0; 
} 
``` 
## OUTPUT: 
<img width="541" height="148" alt="Screenshot 2025-10-20 133558" 
src="https://github.com/user-attachments/assets/8ef7e755-8279-4b46-9a49-931582b3a9f3" 
/> 
## RESULT: 
Thus the C program to find the length of the given string is executed successfully. 
# Program 4:
## AIM: 
To write a C program to count the number of punctuation characters in a given string. 
## ALGORITHM: 
```
1) Get a string as a input from the user. 
2) Count the number of punctuation characters using for loop and if else statements. 
3) Print the result using printf() function. 
``` 
## PROGRAM: 
``` 
#include<stdio.h> 
#include<ctype.h> 
#include<string.h> 
int main() 
{ 
    char str[100]; 
    fgets(str,sizeof(str),stdin); 
    int count=0; 
    for(int i=0;str[i]!='\0';i++) 
    { 
        if(str[i]==','||str[i]=='.'||str[i]=='!') 
        count++; 
    } 
    printf("%d",count); 
} 
``` 
## OUTPUT: 
<img width="538" height="146" alt="Screenshot 2025-10-20 135551" 
src="https://github.com/user-attachments/assets/47185009-7ce2-4fc3-b633-bc2ba64e0fcb" 
/> 
## RESULT: 
Thus the C program to count the number of punctuation characters is executed successfully. 
# Program 5:
## AiM: 
To write a C program to count the number of blank spaces in the given string.  
## ALGORITHM: 
```
1) Get a string as input from the user. 
2) Count the number of blank spaces in the string using for loop and if else statements. 
3) Print the result using printf() function. 
``` 
## PROGRAM: 
``` 
#include<stdio.h> 
#include<ctype.h> 
#include<string.h> 
int main() 
{ 
    char str[100]; 
    fgets(str,sizeof(str),stdin); 
    int count=0; 
    for(int i=0;str[i]!='\0';i++) 
    { 
        if(str[i]==' ') 
        count++; 
    } 
    printf("%d",count); 
} 
``` 
## OUTPUT: 
<img width="531" height="147" alt="Screenshot 2025-10-20 140509" 
src="https://github.com/user-attachments/assets/7e50380a-f8d6-4464-be3b-4f2712ce847e" 
/> 
## RESULT: 
Thus the C program to count the number of blank spaces in the given string is successfully 
executed. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
