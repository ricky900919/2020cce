# 2020cce

這是2020程式設計,要放的程式碼倉庫

## 第一個程式 找零錢
```c
#include <stdio.h>
int main()
{
  int a;
  scanf("%d",&a);
  int c=a/50;
  int d=a%50/5;
  int e=a%50%5/1;
  printf("%d=50*%d+5*%d+1*%d\n",a,c,d,e);
  }
  
 ```
 
## 第二個程式 因數個數
```c
#include <stdio.h>
int main()
{
   int a;
   scanf("%d",&a);
   
   int r=0;
   for(int i=1;i<=a;i++)
   {
      if(a%i==0)
      {
      
       r++;
      
      }
   
   
   }
 
     printf("%d\n",r);


}
```
