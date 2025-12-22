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

include<stdio.h>


int main(){
    int age;
printf("enter age : ");
scanf("%d", &age);

if(age >= 18){
printf("adult \n");
}
else if(age > 13 && age <18){
    printf("teenager \n");
}
else{
    printf("child");
}
return 0;
}
    
    
