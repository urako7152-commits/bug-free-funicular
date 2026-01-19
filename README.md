#include<stdio.h>
int main()
{
    int i, a[5];
    printf("整数を入力してください\n");
    for(i=0; i<5; i++){
        scanf("%d", &a[i]);
    }
    for(i=0; i<5; i++){
        if(a[i]%2!=0){
            printf("%dは奇数である\n", a[i]);
        }
    }
    return 0;
}