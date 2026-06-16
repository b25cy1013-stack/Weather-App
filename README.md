#include<stdio.h>

int main(){
float temperature;
int humidity;
printf("Enter temperature (C):\n");
scanf("%f",&temperature);
printf("Enter humidity (%%): \n");
scanf("%d",&humidity);
printf("------WEATHER 🌡️ REPORT----\n-");
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
if(humidity>80){
printf("humidity: very high \n");
}
else if(humidity>60)
{
printf("humidity: high \n");
}
else if(humidity>30){
    printf("humidity : normal \n");
}
else
printf("humidity : low");
return 0 ;

}

}
}
