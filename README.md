## MCQ Type C Programming [Solved]:name_badge:
> Here is a listing of C interview questions along with answers, explanations and/or solutions: :arrow_down:
## [Follow Here](https://github.com/0xSingh/) :heavy_check_mark: IDE Prefered:[Click Here ](https://ideone.com/)  :heavy_check_mark:
 
|                                `What will be the output of the following C code?`                                |
|--------------------------------------------------------------------------------------------------------------------|
##  [ ] Topic: Input-output in C
```C
1.     #define MSSG "Hello world\n"
       printf (MSSG);
 ```
[ ] Answer : Hello world [ define is pre processor statement in C Language. All statements prefixed with # are preprocessor statements ]
```c
2.      Printf("indian\b\n");
      	Printf("new\rDelhi\n");
```
[ ] Answer : [\b is a backspace escape sequence. /r is "carriage return" character. It will move the cursor to the left side of the screen but will not move down a line.]
 indian
new
Delhi
```c
3.      int a=11;
        Printf("a=%d\t",a);
        Printf("a=%o\t",a);
	Printf("a=%x\t",a);
	Printf("a=%x\n",a); 
```
[ ] Answer :  a=11    a=13    a=b     a=b
```c
4.      int a=4000000000;
        Unsigned int b=4000000000;
        Printf ("a=%d,b=%u\n",a,b);
        Printf("a=%d,b=%u\n",INT_MAX,UINT_MAX);
```
[ ] Answer : a=-294967296,b=4000000000
                        a=2147483647,b=4294967295
```c
5.      char ch;
        Printf("Enter a character:");
	Scanf("%c",&ch);
	Printf("%d\n",ch);
```
 [ ] Answer : Enter a character:a,97
```c
6.      float b=123.1265;
        Printf("%f\t",b);
	Printf("%.2f\t",b);
        Printf("%.3f\n",b);
```
[ ] Answer : 123.126503	123.13	123.127
```c
7.
         int a=625,b=2394,c=12345;
	 printf("%5d,%5d,%5d\n",a,b,c);
	 printf("%3d,%4d,%5d\n",a,b,c);
 ```
[ ] Answer :[2 space Gap]625,[1space]2394,12345
                                   625,2394,12345
 ```c
8.
          int a=98;
	  char ch='c';
          Printf("%c,%d\n",a,ch);
```
[ ] Answer: b,99
```c
9.            float a1,b1,a2,b2,a3,b3;
	      a1=2;
	      b1=6.8;
	      a2=4.2;
              b2=3.57;
	      a3=9.82;
	      b3=85.673;
	      Printf("%3.1f,%4.2f\n",a1,b1);
	      Printf("%5.1f,%6.2f",a2,b2);
	      Printf("%7.1f,%8.2f\n",a3,b3);
 ```  
[ ] Answer : 
2.0,6.80
  4.2,  3.57    9.8,   85.67
 ```c
10.
            Printf("%10s\n","India");
	    Printf("%4s\n","India");
	    Printf("%.2s\n","India");
	    Printf("%5.2s\n","India");
```
 [ ] Answer : 
   India
India
In
   In
   ## [ ] Topic:  Control Flow Statements in C
```C
1.    double f1 = 0.1;
      if (f1 == 0.1)
      printf("equal\n");                       
      else                                                 
      printf("not equal\n");        
```
[ ] Answer : Not Equal [ 0.1 is by default represented as a Double ] Replace Float into Double to Get your desired answer
```c 
2.      j = 10;
        printf("%d\n", j++);                   
```
[ ] Answer : Compile time error: " j " is undeclared [ use int for result ]
```c
3.      for (int k = 0; k < 10; k++);
        return 0;              
```
[ ] Answer : Depends on C standerd Set by the Compiler
```c
4.     int a =9;
       if (a==5)
       printf ("a is five\t");               
       else
       ("a is not five\t");
       printf("Value of a is %d\n",a);
```
[ ] Answer : a is not five     Value of a is 9
```c
5.      int a=20,b=3;
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
[ ] Answer : My name is Akash [ True =1,False=0 <!a=!true=false so !a<10 is true 
                                b=0 so !b=!false=true where c=0 means false ]
```c
7.
        int i=1,j=9;
         if (i>=5 && j<5)                      
         i=j+2;
         printf ("%d\n",i);
         return 0; 
 ```
[ ] Answer : 1[True && False is False which is 0]
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
             printf ("%d",i++);
             i=0;
             while (i<5)
             printf ("%d",i++);
             return 0; 
 ```  
[ ] Answer : 5 10 01234 [ First For loop Executed Succesfully {5} , 2nd While Loop not executed but due to printf function,value of i printed once  ,
3rd While loop executed successfully , and it will Return 0 1 2 3 4 ]
 ```c
10.
        int x = 5;
        if (x < 1)
            printf("hello");
        if (x == 5)
            printf("hi");
        else
            printf("no");
    }
  ```
 [ ] Answer : hi 
 ```c
 11.     int a = 0, i = 0, b;
        for (i = 0;i < 5; i++)
        {
            a++;
            continue;
        }
 ```
 [ ] Answer : 5
 ```c
12.  int a = 0, i = 0, b;
        for (i = 0;i < 5; i++)
        {
            a++;
            if (i == 3)
                break;
        }
```
[ ] Answer: 4
 ```c
13.     int i = 0, j = 0;
        for (i = 0;i < 5; i++)
        {
            for (j = 0;j < 4; j++)
            {
                if (i > 1)
                    break;
            }
            printf("Hi \n");
        }
```
[ ] Answer: Hi is printed 5 times
```c
14.          int i = 0;
        int j = 0;
        for (i = 0;i < 5; i++)
        {
            for (j = 0;j < 4; j++)
            {
                if (i > 1)
                    continue;
                    printf("Hi \n");
            }
        }
```
[ ] Answer : Hi is printed 8 times
```c
15.        int i = 0;
        for (i = 0;i < 5; i++)
            if (i < 4)
            {
                printf("Hello");
                break;
            }
 ```
 [ ] Answer : Hello
|Stay Tuned ,I will upload more problems based on Other Topics|
|-------------------------------------------------------------|
