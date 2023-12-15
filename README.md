#include <stdio.h>

int main() {
    int N, sum = 0;

    // Kullanıcıdan N sayısını al
    printf("N sayisini girin: ");
    scanf("%d", &N);

    // 1'den N'e kadar olan tek sayıları topla
    for (int i = 1; i <= N; i += 2) {
        sum += i;
    }

    // Sonucu ekrana yazdır
    printf("1'den %d'e kadar olan tek sayilarin toplami: %d\n", N, sum);

    return 0;
}
