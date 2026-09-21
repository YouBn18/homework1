# 전유빈의 첫 개인리포트
# 소감
- for반복문에 대해서 다시 복습을 하게 돼서 예전의 감을 다시 살려냄

---
교수님 감사합니다
---
"""
#include <stdio.h>

void main() {

   int n;
   scanf_s("%d", &n);
   for (int i = 0; i < (n / 2) + 1; i++) {
      for (int j = 0; j < i; j++) {
         printf(" ");
      }
      for (int j = 0; j < n - (i*2); j++) {
         printf("*");
      }
      printf("\n");
   }

   for (int i = (n/2) - 1; i >= 0 ; i--) {
      for (int j = 0; j < i; j++) {
         printf(" ");
      }
      for (int j = 0; j < n - (i * 2); j++) {
         printf("*");
      }
      printf("\n");
   }
}
"""
