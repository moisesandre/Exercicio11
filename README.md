# Exercicio11

#include <stdio.h>
#include <stdlib.h>

int main()

{
    system("color 0b");
    int i, maior[5], n=0;

    for (i=0; i<=4; i++)
    {
        printf("Digite um numero: \n");
        scanf("%d", &maior[i]);
    }

    n=maior[i];

    for (i=0; i<=4; i++)
    {
        if (n<maior[i])
        {
            n=maior[i];
        }
    }

    printf("O maior numero digitado e: %d\n", n);

return 0;
}
