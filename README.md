# TEAM CODING PRACTICE
1)

#include <stdio.h>

int main()
{
    char ch;
    int a;
    scanf("%c %d", &ch, &a);
    int result = sizeof(ch) * sizeof('A') % sizeof(100);
    result = result * (sizeof(char) + sizeof(int));
    result = result > sizeof(ch);
    result = ch * result + a + ch;
    printf("%d", result);
    return 0;
}


OUTPUT:
231

