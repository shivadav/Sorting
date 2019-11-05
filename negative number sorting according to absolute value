#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
void main()
{
  int ar[10],i,j,temp;
  for(i=0;i<10;i++)
  {
    scanf("%d",&ar[i]);
  }
  for(i=0;i<10;i++)
  {
    for(j=0;j<10-i-1;j++)
    {
      if(abs(ar[j])>abs(ar[j+1]))
      {
        temp=ar[j];
        ar[j]=ar[j+1];
        ar[j+1]=temp;
      }
    }
  }
  for(i=0;i<10;i++)
  {
    printf("%d ",ar[i]);
   }
getch();
}
