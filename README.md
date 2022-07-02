//2.gorevin 2.kısmı
#include <stdio.h>

int main() {
   int a;
   int b;
   int c;
   printf("1.degeri giriniz");
   scanf("%d",a);
   printf("2.degeri giriniz");
   scanf("%d",b);
   printf("3.degeri giriniz");
   scanf("%d",c);
   if(a>=b&a>=c)
   printf("en buyuk deger %d",a);
   if(b>=a&b>=c)
   printf("en buyuk deger %d",b); 
   if(c>=a&c>=b)
   printf("en buyuk deger %d",c);

    return 0;}
