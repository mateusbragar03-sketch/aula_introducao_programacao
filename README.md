#include <stdio.h>

int main() {
    float nota;
    
    printf("digite a nota: ");
    scanf("%f", &nota);
    
    if (nota >= 6) {
      printf("aprovado\n");
    } else {
       printf("reprovado\n");
    }
    

    return 0;
}
