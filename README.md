# Learn
总结
#include<stdio.h>
int main() {
    int seconds, h, m, s;
    scanf("%d", &seconds);
    h = seconds / 3600;
    m = (seconds % 3600) / 60;
    s = (seconds % 3600) % 60;
    printf("%d %d %d", h, m, s);}
//时间转换

#include<stdio.h>
int main()
{
    int Q;
    int W;
    int E;
    int R;
    int T;
    scanf("%d %d %d %d %d", &Q, &W, &E, &R, &T);
    printf("%0.1F", (Q + W + E + R + T) / 5.0);
    return 0;
}
//学生成绩浮点、

