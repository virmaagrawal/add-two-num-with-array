# add-two-num-with-array and print array element index

#include<stdio.h>

int main()

{
        int sum,n,i,j,t,flag=0;

        int a[]={1,2,7,11,58};

        n=sizeof(a)/sizeof a[0];
       printf("enter target..\n");

        scanf(" %d",&t);

        for(i=0;i<n;i++)

        {
              for(j=i+1;j<n;j++)

                {

                sum=a[i]+a[j];

                if(sum==t)

                {

        printf("output:[%d, %d]\n",i,j);

        flag++;

        }

        }

        }

        if(flag==0)

                printf("The t %d is not found\n",t);

}



