
#include <stdio.h>
int main() {
    int i,temp,j,min,n;
    printf("Enter no. of elements:");
    scanf("%d",&n);
    int a[n];
    printf("Enter the elements:");
    for (i=0;i<n;i++){
        scanf("%d",&a[i]);
    }
    for (i=0;i<n-1;i++){
        min=i;
        for (j=i+1;j<n;j++){
            if (a[min]>a[j]){
                min=j;
            }
        }
        if (i!=min){
            temp=a[i];
            a[i]=a[min];
            a[min]=temp;
        }
    }
    printf("Sorted Array:");
    for (i=0;i<n;i++){
        printf("%d  ",a[i]);
    }
    return 0;
}
