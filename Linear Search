#include<stdio.h>
int main() {
    int x,n,i,count=0;
    printf("Enter the no. of elements:");
    scanf("%d",&n);
    int a[n];
    printf("Enter the elements:");
    for (i=0;i<n;i++){
        scanf("%d",&a[i]);
    }
    printf("Enter the value to be found:");
    scanf("%d",&x);
    for (i=0;i<n;i++){
        if (a[i]==x){
            count++;
            printf("\nNumber found at index %d",i);
        }
    }
    if (count>0){
        printf("\nNumber found %d times",count);
    }
    else printf("Number not found.");
    return 0;
}
