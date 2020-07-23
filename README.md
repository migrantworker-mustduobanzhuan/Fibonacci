# Fibonacci
求Fibonacci数练习递归
#include<stdio.h>
int f(int n){

				if(n==1||n==2)
        
					return 1;
          
				else
				return f(n-1)+f(n-2);
        


			}


int main(){


			int a[1000];
      
			int i,n;
      
			scanf("%d",&n);
      
			for(i=1;i<=n;i++){
      
							a[i]=f(i);	
              
							printf("f（%d）=%d\n",i,a[i]);
              
			
							}

			}
