# The-sum-of-its-digits
#include <stdio.h>
#include <math.h>
int main() {
	
    int n,l,sum=0;
    scanf("%d", &n);
    while(n!=0){
        l=n%10;
        sum+=l;
        n=n/10;
    }
    printf("%d",sum);
    return 0;
}
