#include <stdio.h>

int main() 
   {
    int t1, t2, t3;
    double ttime;

    // вводимо значення трьох часів гостей
    printf("введіть час t1: ");
    scanf("%d", &t1);
    printf("введіть час t2: ");
    scanf("%d", &t2);
    printf("введіть час t3: ");
    scanf("%d", &t3);

    // вираховуємо загальний час
    ttime = 1 / (1.0/t1 + 1.0/t2 + 1.0/t3);

    // виводимо загальний час з точністю до двох знаків після коми
    printf("загальний час: %.2f hours\n", ttime);

    return 0;
}
