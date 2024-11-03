#include <stdio.h>

int main() {
    int x, n, i,mid,flag = 0;
    printf("\nEnter the number of elements: ");
    scanf("%d", &n);
    int left=0, right= n-1;

    int a[n]; // Variable-length array
    printf("\nEnter the elements in ascending order: ");
    for (i = 0; i < n; i++) {
        scanf("%d", &a[i]);
    }
    printf("\nEnter the value to be found: ");
    scanf("%d", &x);

    while (left<=right) {
        mid= (left+right)/2;
        if (x == a[mid]) {
            flag=1;
            break;
        }
        if (x>a[mid]) {
            left= mid+1;
        }
        if (x<a[mid]){
            right= mid-1;
        }
    }

    if (flag==1) {
        printf("\nNumber found at index %d", mid);
    } else {
        printf("\nNumber not found.");
    }
    return 0; 
}
