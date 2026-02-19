#include<stdio.h>


int main(){<br>
    int age;<br>
printf("enter age : ");<br>
scanf("%d", &age);<br>

if(age > 18){<br>
printf("adult \n");<br>
printf("they can vote \n");<br>
printf("they can drive \n");<br>
}<br>
else{<br>
    printf("not adult \n");<br>
}<br>
    
    

    return 0;<br>
}<br>

#include<stdio.h><br>


int main(){<br>
    int age;<br>
printf("enter age : ");<br>
scanf("%d", &age);<br>

if(age >= 18){<br>
printf("adult \n");<br>
}<br>
else if(age > 13 && age <18){<br>
    printf("teenager \n");<br>
}<br>
else{<br>
    printf("child");<br>
}<br>
return 0;<br>
}<br>  


  #include<stdio.h><br>
  
int main(){<br>
    char ch;<br>
    printf("enter character :");<br>
    scanf("%c", &ch);<br>

    if(ch >= 'A' && ch <= 'Z') {<br>
        printf("upper case \n");<br>
    }<br>
    else if(ch >= 'a' && ch <='z') {<br>
        printf("lower case \n");<br>
    }<br>
    else{<br>
        printf("not english letter \n");<br>
    }<br>
      return 0;<br>
      } <br>

  

#include<stdio.h><br>

int main(){<br>
   int n;<br>
   printf("enter number : ");<br>
   scanf("%d", &n);<br>

   int sum = 0;<br>
   for(int i=1, j=n;  i<=n && j>=1; i++,j--){<br>
    sum = sum + i;<br>
    printf("%d\n",j);<br>
   }<br>
   printf("sum is %d \n", sum);<br>
   
return 0;<br>
}<br>




    
#include<stdio.h><br>

int main(){<br>
int n;<br>
printf("enter number :");<br>
scanf("%d \n",&n);<br>
 
int fact = 1;<br>
for(int i=1; i<=n; i++){<br>
    fact = fact * i;<br>
}<br>
printf("final factorial is %d", fact);<br>

    return 0;<br>
}<br>

#include <stdio.h><br>
int fib(int n);<br>
int main() {<br>
    fib(6);<br>
    return 0;<br>
}<br>
int fib(int n){<br>

if (n==0){<br>
    return 0;<br>
}<br>
if (n==1){<br>
    return 1;<br>
}<br>
int fibNm1=fib(n-1);<br>
int fibNm2=fib(n-2);<br>
int fibn=fibNm1+fibNm2;<br>
printf("fib of %d is %d\n",n,fibn);<br>

}<br>


#include <stdio.h><br>
#include <math.h><br>

int main() {<br>
    int x1, y1, x2, y2;<br>
    int dx, dy;<br>
    float abs_dx, abs_dy, total_distance;<br>

    printf("Enter x1 y1: ");
    scanf("%d %d", &x1, &y1);

    printf("Enter x2 y2: ");
    scanf("%d %d", &x2, &y2);

    dx = x2 - x1;
    dy = y2 - y1;

    abs_dx = sqrt(dx * dx);
    abs_dy = sqrt(dy * dy);

    total_distance = abs_dx + abs_dy;

    printf("Manhattan Distance = %.0f", total_distance);

    return 0;
    }
    

#include <stdio.h><br>

int main() {<br>
   float price[3];<br>
   printf("Enter 3 price:");<br>
   scanf("%f",&price[0]);<br>
   scanf("%f",&price[1]);<br>
   scanf("%f",&price[2]);<br>

   printf("total price 1 : %f\n",price[0]+(0.18*price[0]));<br>
   printf("total price 2 : %f\n",price[0]+(0.18*price[1]));<br>

printf("total price 3 : %f\n",price[0]+(0.18*price[2]));<br>>


    return 0;<br>
}<br>
    
#include<stdio.h><br>
int main(){<br>
   float price[3];<br>
   printf("enter 3 prices:");<br>
   scanf("%f",&price[0]);<br>
   scanf("%f",&price[1]);<br>
   scanf("%f",&price[2]);<br>

   printf("total price 1:%f\n",price[0]+(0.18*price[0]));<br>
   printf("total price 2:%f\n",price[0]+(0.18*price[1]));<br>
   printf("total price 3:%f\n",price[0]+(0.18*price[2]));<br>

   
    return 0;<br>
}<br>
    
#include<stdio.h><br>

int main(){<br>
  int age = 22;<br>
  int _age = 23;<br>
  int *ptr = &age;<br>
  int*_ptr = &_age;<br>
  
  printf("difference = %u\n",ptr-_ptr);<br>
  _ptr =&age;<br>
  printf("comparison = %u\n", ptr == _ptr);<br>
  
   
    return 0;<br>
}<br>
   #include<stdio.h><br>
int main(){<br>
    int a,b,c,n=1;<br>
    do{<br>
        printf("enter your choice \n");<br>
        printf("enter 1 for addition \n");<br>
        printf("enter 2 for subtraction \n");<br>
        printf("enter 3 for multiplication  \n");<br>
        printf("enter 4 for division \n");<br>
        printf("enter 5 for exit \n");<br>
        scanf("%d",&n);<br>
        switch(n){<br>
            case 1:<br>
            printf("enter 2 no:\n");<br>
            scanf("%d%d",&a,&b);<br>
            c = a + b;<br>
            printf("addition = %d\n",c);<br>
            break;<br>
             case 2:<br>
            printf("enter 2 no:\n");<br>
            scanf("%d%d",&a,&b);<br>
            c = a - b;<br>
            printf("subtraction = %d\n",c);<br>
            break;<br>
             case 3:<br>
            printf("enter 2 no:\n");<br>
            scanf("%d%d",&a,&b);<br>
            c = a * b;<br>
            printf("mltiplication = %d\n",c);<br>
            break;<br>

             case 4:<br>
            printf("enter 2 no:\n");<br>
            scanf("%d%d",&a,&b);<br>
            c = a / b;<br>
            printf("division = %d\n",c);<br>
            break;<br>
             case 5:<br>
            printf("ready to exit from execution \n");<br>
            break;<br>
            default:<br>
            printf("wrong choice\n");<br>
        }<br>
    }<br>
    while(n != 5);<br>
    return 0;   <br>
}<br>

   


 
