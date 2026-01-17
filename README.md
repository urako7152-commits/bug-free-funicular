#include<iostream>
#include<stdio.h>
int sum(int a);
int main(){
int b, c;
int d=0;
printf("正の整数を入力してください\n");
scanf_s("%d", &b);
for(c=1; c<=b; b+=2){
d+=c}
printf("奇数の和は%d\n",d);
return 0;}
int sum(int a){
int c=0;
c+=a;
returnc;}
