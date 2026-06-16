#include<stdio.h>

int main(){
float temperature;
int humidity;
printf("Enter temperature (C):\n");
scanf("%f",&temperature);
printf("Enter humidity (%%): \n");
scanf("%d",&humidity);
printf("------WEATHER 🌡️ REPORT------");
if(temperature>35){
printf("weather: 🌞 very hot\n");
}
else if(temperature>25){
printf("weather:🌞 warm\n");
}
else if(temperature>15){
printf("weather:  pleasant \n");
}
else
{
printf("weather: cold \n");
}
if(humidity>70){
printf("humidity: high \n");
}
else if(humidity<=70)
{
printf("humidity: normal \n");
}
return 0 ;

}
}
