# CT4-ASSIGNMENT
#include<stdio.h>
int main(){
    int marks[4];
    int i,sum=0;
    printf("MARKS OBTAINED\n");
    for(i=0;i<=4;i++){
        scanf("%d",&marks[i]);
    }for(i=0;i<5;i++){
        sum=sum+marks[i];
    }float avg=(float)sum/5;
    char c = '%';
    printf("PERCENTAGE:%.2f%",avg,c);
    return 0;
}
