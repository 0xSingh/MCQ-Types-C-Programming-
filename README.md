# MCQ Type C Programming [Solved]:name_badge:
> Here is a listing of C interview questions along with answers, explanations and/or solutions::arrow_down:
## [Follow Here](https://github.com/0xSingh/) :heavy_check_mark: IDE Prefered:[Click Here ](https://ideone.com/)  :heavy_check_mark:
 
|                                `What will be the output of the following C code?`                                |
|--------------------------------------------------------------------------------------------------------------------|
```
1.double f1 = 0.1;
   if (f1 == 0.1)
      printf("equal\n");            | Answer : Not Equal [ 0.1 is by default represented as a Double ]  |
      else                          |         Replace Float into Double to Get your desired answer      |
      printf("not equal\n");        |-------------------------------------------------------------------|
```
```
2.    j = 10;
        printf("%d\n", j++);         Answer : Compile time error: " j " is undeclared [ use int for result ]
        return 0; */

```
```
3. for (int k = 0; k < 10; k++);     Answer : Depends on C standerd Set by the Compiler
        return 0; */

```
```
4.  int a =9;
       if (a==5)
       printf ("a is five\t");                 Answer : a is not five     Value of a is 9
       else
        ("a is not five\t");
       printf("Value of a is %d\n",a);
       return 0; */
 ```
```
5.   int a=20,b=3;
        if(a<10)
            a=a-5;                             Answer : a=20    b=3
            b=b+5;
        printf ("a=%d   b=%d\n",a,b);
        return 0; */
```
```
6.  int a=9,b=0,c=0;
          if(!a<10  && !b||c)
          printf ("My name is Akash\n");        Answer : My name is Akash
          else
          printf ("My Surname is Singh\n");
          return 0; */
```
```
7.
        int i=1,j=9;
         if (i>=5 && j<5)                       Answer : 1 [True && False is False which is 0]
         i=j+2;
         printf ("%d\n",i);
         return 0; */
 ```
 ```
8.
           int j,k,i;                           
           for (k=1;k<=3;k++)                   Answer: Compile it on Ideone.com or any other IDE
            {
               for (j=1;j<=6;j++)                
               {
                   for(i=1;i<=6;i++)
                    printf("*");
                    printf("\n");
               }
               printf("\n");
           }
           return 0; */
```
```
9.    int i ;
             for (i=1;i<5;i++);
             printf ("%d ",i);
             i=10;                           Answer : 5 10 01234 [ First For loop Executed Succesfully {5} , 2nd While Loop not executed , 3rd While 
             while (i<5);                                               loop executed successfully , and it will Return 0 1 2 3 4 ]
             printf ("%d ",i++);
             i=0;
             while (i<5)
                printf ("%d",i++);
             return 0; */
 ```            
|Stay Tuned ,I will upload more problems based on Other Topics|
|-------------------------------------------------------------|
