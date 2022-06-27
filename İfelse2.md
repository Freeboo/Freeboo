#include <stdio.h>

int main(){
int x,y,z;

printf("Birinci sayıyı giriniz");
scanf("%d, &x");

printf("İkinci sayıyı giriniz");
scanf("%d,&y");

printf("Ücüncü sayıyı giriniz");
scanf("%d,&z");

if (x<y<z)
printf("Minimum değer",&x);
else if(y<x<z)
printf("Minimum değer",&y);
else if(z<x<y)
printf("Minimum değer",&z);
else if(x<z<y)
printf("Minimum değer",&x);
else if(y<z<x)
printf("Minimum değer",&y);
else
printf("Minimum değer",&z);
}
