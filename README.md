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

## 第三個程式 找倍數
```c
#include <stdio.h>
int main()
{
   int n=10,r=0,a[10];
   for(int i=0;i<n;i++)
   {
     scanf("%d",&a[10]);
     if(a[10]%3==0) r++;
         
   }
 
      
       printf("%d\n",r);   
}   
```





## 第四個程式 整數轉換為等級
```c
#include <stdio.h>
int main()
{
  int n;
  scanf("%d",&n);
  if(n>90||n==90)printf("a");
  else if(n<90&&n>80||n==80)printf("b");
  else if(n<80&&n.60||n==60)printf("c");
  else printf("f");
}
```


## 第五個程式 分式化簡
```c
#include <stdio.h>
int main()
{
 
  int a,b,i ,ans=1;
  scanf("%d %d",&a,&b);
  for(int i=1;i<=b;i++)
  {
    if(a%i==0&&b%i==0)
     ans=i;
  
  
  }
 
    printf("%d %d\n",a/ans,b/ans);

}
```
