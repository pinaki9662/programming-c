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


    
    




    
