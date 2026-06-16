#include<stdio.h>

int main(){
float temperature;
int humanidity;
printf("Enter temperature (C):\n");
scanf("%f",&temperature);
printf("Enter humanidity (%%): \n");
scanf("%d",&humanidity);
if(temperature>35){
printf("weather: very hot\n");
}
else if(temperature>25){
printf("weather: warm\n");
}
else if(temperature>15){
printf("weather: pleasant \n");
}
else
{
printf("weather: cold \n");
}
if(humanidity>70){
printf("humanidity: high \n");
}
else if(humanidity<=70)
{
printf("humanidity: normal \n");
}
return 0 ;

}
