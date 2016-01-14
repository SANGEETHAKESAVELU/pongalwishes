#include<stdio.h>
#include<unistd.h>
#include<Windows.h>
int main()
{
  int i;
  char a[]={"HAPPY PONGAL"};
  for(i=0;i<=11;i++)
  {
    Sleep(1000);
    printf("%c",a[i]);
  }
  return 0;
}
