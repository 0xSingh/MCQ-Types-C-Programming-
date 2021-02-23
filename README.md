## MCQ Type C Programming [Solved]:name_badge:
> Here is a listing of C interview questions along with answers, explanations and/or solutions: :arrow_down:
## [Follow Here](https://github.com/0xSingh/) :heavy_check_mark: IDE Prefered:[Click Here ](https://ideone.com/)  :heavy_check_mark:
 
|                                `What will be the output of the following C code?`                                |
|--------------------------------------------------------------------------------------------------------------------|

##  [ ] Topic: Control Flow Statements in C
```C
1.double f1 = 0.1;
   if (f1 == 0.1)
      printf("equal\n");                       
      else                                                 
      printf("not equal\n");        
```
[Answer : Not Equal [ 0.1 is by default represented as a Double ] Replace Float into Double to Get your desired answer
```c
2.    j = 10;
        printf("%d\n", j++);                   
```
[ ] Answer : Compile time error: " j " is undeclared [ use int for result ]
```c
3. for (int k = 0; k < 10; k++);
return 0;              
```
[ ] Answer : Depends on C standerd Set by the Compiler
```c
4.  int a =9;
       if (a==5)
       printf ("a is five\t");               
       else
        ("a is not five\t");
       printf("Value of a is %d\n",a);
```
[ ] Answer : a is not five     Value of a is 9
```c
5.   int a=20,b=3;
        if(a<10)
            a=a-5;                            
            b=b+5;
        printf ("a=%d   b=%d\n",a,b);
 ```
 [ ] Answer : a=20    b=3
```c
6.  int a=9,b=0,c=0;
          if(!a<10  && !b||c)
          printf ("My name is Akash\n");        
          else
          printf ("My Surname is Singh\n");
          return 0; 
```
[ ] Answer : My name is Akash [ Explaination: ]
```c
7.
        int i=1,j=9;
         if (i>=5 && j<5)                      
         i=j+2;
         printf ("%d\n",i);
         return 0; 
 ```
[ ] Answer : 1 [True && False is False which is 0]
 ```c
8.
           int j,k,i;                           
           for (k=1;k<=3;k++)                   
            {
               for (j=1;j<=6;j++)                
               {
                   for(i=1;i<=6;i++)
                    printf("*");
                    printf("\n");
               }
               printf("\n");
           }
           return 0; 
```
[ ] Answer: Compile it on Ideone.com or any other IDE
```c
9.    int i ;
             for (i=1;i<5;i++);
             printf ("%d ",i);
             i=10;                          
             while (i<5);                                             
             i=0;
             while (i<5)
                printf ("%d",i++);
             return 0; 
 ```  
[ ] Answer : 5 10 01234 [ First For loop Executed Succesfully {5} , 2nd While Loop not executed , 3rd While   loop executed successfully , and it will Return 0 1 2 3 4 ]
             printf ("%d ",i++);
|Stay Tuned ,I will upload more problems based on Other Topics|
|-------------------------------------------------------------|
