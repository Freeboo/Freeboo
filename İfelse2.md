#include <stdio.h>

int main(){
int x,y,z;

printf("Birinci sayıyı giriniz");
scanf("%d", &x);

printf("İkinci sayıyı giriniz");
scanf("%d", &y);

printf("Ücüncü sayıyı giriniz");
scanf("%d", &z);

if (x<y){
if (x<z)
printf("Minimum değer %d ",x);}
else if(y<z){
if     (y<x)
printf("Minimum değer %d ",y);}
else {
printf("Minimum değer %d ",z);}
}
