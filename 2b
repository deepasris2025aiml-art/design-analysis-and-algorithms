#include <stdio.h>

int main() {
    int V;
    if (scanf("%d", &V) != 1) return 0;

    int denominations[] = {1000, 500, 100, 50, 20, 10, 5, 2, 1};
    int n = sizeof(denominations) / sizeof(denominations[0]);
    int count = 0;

    for (int i = 0; i < n; i++) {
        if (V >= denominations[i]) {
            count += V / denominations[i];
            V %= denominations[i];
        }
    }

    printf("%d\n", count);
    return 0;
}
