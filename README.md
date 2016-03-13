# exercitiisda
#include<stdio.h>
#include<stdlib.h>
#include<string.h>
int main()
{
    char sir[256];
    int i,lungime;
    scanf("%s",sir);
    lungime=strlen(sir);
    for(i=0;i<lungime;i++)
    {
        if(sir[i]<=57 && sir[i]>=48)
        {
            printf("%c",sir[i]);
        }
    }
    return 0;
}
