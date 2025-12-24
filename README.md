Program-2-a
C-Module 2
EX_NO-02)a)-Loop
Date: 24/12/25
Name: SHIVANI K
Register Number:25013585


AIM:

Write a C Program to print the string "LINUX" n number of times.

ALGORITHM:

Start the program.

Declare an integer variable to store the input value.

Read the integer value from the user using the scanf function.

Use a for loop starting from 1 to the input value:

a. In each iteration, print "LINUX".

End the program.

PROGRAM:
```
#include <stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    for(int i=1;i<=num;i++)
    {
        printf("LINUX\n");
    }
return 0;
}
```


OUTPUT:

![WhatsApp Image 2025-12-24 at 11 00 17 PM](https://github.com/user-attachments/assets/58283ea4-4e3c-4417-910f-4f0ab8c0d4bc)



RESULT:


Thus the program to print the string "LINUX" n number of times has been executed successfully.








Program-2-b
C-Module 2
EX_NO-02)b)-Nested Loops



AIM:

write a c program to print hollow rectangular pattern

ALGORITHM:

Start the program.

Declare two integer variables to store the number of rows and columns.

Read the values of rows and columns from the user using the scanf function.

Use a for loop from 1 to the number of rows:

a. Inside this loop, use another for loop from 1 to the number of columns:

 i. If the current row or column is the first or last, print "*".

 ii. Otherwise, print a space " ".
b. After the inner loop, move to the next line using printf("\n").

End the program.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int row,col;
    scanf("%d\n%d",&row,&col);
    for(int i=1;i<=row;i++){
        for(int j=1;j<=col;j++){
            if(i==1||j==1||i==row||j==col)printf("*");
            else printf(" ");
        }printf("\n");
    }
return 0;
}
```


OUTPUT:


![WhatsApp Image 2025-12-24 at 11 28 52 PM](https://github.com/user-attachments/assets/618ae1c3-9902-4a99-b3ba-558f2ebaacad)




RESULT:


Thus the program to print hollow rectangular pattern has been executed successfully.





Program-2-c
C-Module 2
EX_NO-02)c)-FUNCTIONS



AIM:

Write a C program to perform multiplication and division of two numbers using functions (With argument and without return type).

ALGORITHM:

Start the program.

1. Declare two float variables to store the input numbers.

2. Read the two float numbers from the user using the scanf function.

3. Define a function to perform multiplication:

a. Take two float arguments.

b. Multiply the two numbers and store the result.

c. Print the multiplication result.

4. Define a function to perform division:

a. Take two float arguments.

b. Divide the first number by the second and store the result.

c. Print the division result with six decimal places.

5. In the main function, call the multiplication function with the input numbers.

6. Call the division function with the input numbers.

7. End the program.

PROGRAM:
```
#include<stdio.h>
void mul(float a,float b){
    float c=a*b;
    printf("Multiplication: %.f",c);
}
void div(float a,float b)
{
    float c=a/b;
    printf("\nDivision: %.6f",c);
}
int main()
{
    float a,b;
    scanf("%f\n%f",&a,&b);
    mul(a,b);
    div(a,b);
}
```
OUTPUT:


![WhatsApp Image 2025-12-24 at 11 29 34 PM](https://github.com/user-attachments/assets/21ad010f-5daf-4554-b6bc-9c0738af14a8)



RESULT:


Thus the program to perform multiplication and division of two numbers using functions (With argument and without return type) has been executed successfully.






Program-2-d
C-Module 2
EX_NO-02)d)-LOOPS

AIM:

Write a c program to find the sum of Odd digits using while loop in a Given range

ALGORITHM:

1. Start the program.

2. Declare three integer variables: num1, num2, and sum. Initialize sum to 0.

3. Read two integer values (num1 and num2) from the user using scanf.

4. Assign the value of num1 to a variable n.

5. Use a while loop that runs as long as n is less than or equal to num2:

a. Check if n is an odd number (n % 2 != 0). i. If true, add n to sum.

b. Increment n by 1.

6. After the loop ends, print the value of sum.

7. End the program.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,n,sum=0;
    scanf("%d\n%d",&num1,&num2);
    n=num1;
    while(n<=num2){
        if(n%2!=0)
        {
            sum+=n;
        }
        n++;
    }
    printf("%d",sum);
}
```


OUTPUT:


![WhatsApp Image 2025-12-24 at 11 30 11 PM](https://github.com/user-attachments/assets/d2a5fb6a-1ffb-47d4-ab45-efaa7afe28b4)



RESULT:


Thus the program to find the sum of Odd digits using while loop in a Given range has been executed successfully.








Program-2-e
C-Module 2
EX_NO-02)e)-LOOPS


AIM:

Write a C program to print the multiplication table of a given number using do while loop within the certain limit or range

ALGORITHM:

Start the program.

Declare three integer variables: num1, num2, and i. Initialize i to 1.

Read two integer values (num1 and num2) from the user using scanf.

Use a do-while loop that runs as long as i is less than or equal to num2:

a. Multiply num1 by i and store the result in a variable mul.

b. Print the value of mul followed by a space.

c. Increment i by 1.

End the program.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,i=1;
    scanf("%d\n%d",&num1,&num2);
    do{
        int mul=num1*i;
        printf("%d ",mul);
        i++;
    }while(i<=num2);
}
```



OUTPUT:


![WhatsApp Image 2025-12-24 at 11 30 52 PM](https://github.com/user-attachments/assets/bebc3de7-d996-4f37-b87a-741d935a521b)


RESULT:

Thus the program to print the multiplication table of a given number using do while loop within the certain limit or range has been executed successfully.
