#include <stdio.h>
int main(){
  
  int num;
  
  scanf("%d", &num);
  
  (num % 2 == 0 && (num % 3 == 0 || num % 7 == 0)) ? printf("1"): printf("0");
  return 0;
  
}
