# rtr105
0 uname -a    1 echo $0    2 whoami    3 pwd    4 man ls    5 man pwd    6 pwd --help    7 ls --help    8 manls    9 man ls   10 ls --help   11 uname --help   12 ls -l   13 ls -lt   14 touch --help   15 ls -lt   16 touch test1.txt   17 ls -lt   18 touch -t 202109140000 start   19 ls -lt   20 touch -t 202109140001 readme.txt   21 ls -lt   22 touch -t 202109142359 stop   23 ls -lt   24 history   25 history | grep touch
#include <stdio.h>

int main()
{
    printf("Please enter 2 integer values: ");
    long a, b;

    scanf("%ld %ld", &a, &b);
    printf("%ld\n", a * b);
    return 0;
}
PU2_decTobin.c
#include <stdio.h>

int main()
{
    printf("Ievadiet skaitli (0 - 255)- ");
    char a;
    scanf("%d", &a);
    for (int i =0; i < 8; i++)
        printf("%d", a & (1 << (7 - i)) ? 1 : 0);
    printf("\n");
    return 0;
}
