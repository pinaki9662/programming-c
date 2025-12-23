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

include<stdio.h><br>


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


  include<stdio.h><br>
  
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

  
    
