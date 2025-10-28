# find-char-at-index-and-print-it-by-making-own-function-with-help-of-array-and-pointer.c

// c program to find char at index and print it by making own function with help of array and pointer.

#include <stdio.h>
char mystrchr(char a[],char);

int main() {
    int n;
    char a[30]="this is sick man";
    n=mystrchr(a,'a');
    printf("%d",n);
    return 0;
}

  char mystrchr(char a[],char){
    int w=0;
    while(*a!='a'){
        ++a;
        ++w;
    }
    return w;
}
