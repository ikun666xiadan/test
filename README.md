//#include<stdio.h>
//	int main()
//{
//	char ch;
//		printf("输入一串字符:\n");
//			while((ch=getchar())!='\n')
//{
//	if((ch>='a') && (ch<='z'))
//		ch-='a'-'A';
//	else if((ch>='A') && (ch<='Z'))
//		{
//			ch+='a'-'A';
//		}
//	else
//	{
//		ch=ch+1;
//	}
//	putchar(ch);
//}
//
//	return 0;
//
//}


//#include<stdio.h>
//int main()
//{
//	float R,z;
//	int y;
//	R=12.3;
//	y=1996;
//	printf("输入增长率:0.02,0.015,0.01.0.005四选一\n");
//	scanf("%f",&z);
//	do
//	{
//	R=R*(1+z);
//	y++;
//	}while(R<=13);
//		printf("%d,人口达到:%f\n",y,R);
//	return 0;
//}



//#include <stdio.h>
//int main()
//{
//	float score,sum=0 ,average=0;
//	int n,count=0;
//	printf("enter score:\n");
//	scanf("%f",&score);
//	n=0;
//	sum=0;
//	while(score>0)
//	{
//	  if(score<60)
//	  {
//        printf("不及格的分数:%f\n",score);	  
//	    count=count+1;
//	  }
//		 n++;
//		sum+=score;
//		average=sum/n;
//	}
//	printf("平均成绩:average=%f\n",average);
//	printf("不及格人数: %d\n",count);
//}

//5.29
//
//#include <stdio.h>
//void main()
//{
//	char ch;
//	printf ("please word x:\n");
//	while((ch=getchar())!='\n')
//	{
//	if(ch>='a'&&ch<='z')
//		ch=ch-32;
//	else
//		if(ch>='A'&&ch<='Z')
//			ch=ch+32;
//		else
//			ch=ch+1;
//	putchar(ch);
//	}
//}
//5.38
//
//
//#include <stdio.h>
// void main()
//{
//	float ren,r;
//	int i=1996;
//	ren=12.3;
//	printf("请输入增长率：0.02,0.015,0.01,0.005其中之一\n");
//	scanf("%f",&r);
//	do
//	{
//	
//	i=i+1;
//	ren=ren*(1+r);
//	}while(ren<=13);
//	printf("%d年,人口:%f",i,ren);
//
//}



//5.43
//#include <stdio.h>
//void main()
//{
//	float score,sum=0;
//	int n,count=0;
//	printf("enter score:\n");
//	scanf("%f",&score);
//	n=0;
//	sum=0.0;
//	while(score>0&&n<2000)
//	{
//	  if(score<60)
//	  {
//        printf("%f\n",score);	  
//	    count++;
//	  }
//	sum+=score;
//	n++;
//	scanf("%f",&score);
//	}
//	printf("average=%f\n",sum/n);
//	printf("%d not pass\n",count);
//}
//5.45

//#include <stdio.h>
//int main()
//{
//	int a,b,c,i;
//	for(a=1;a<=9;a++)
//		for(b=0;b<=9;b++)
//			for(c=0;c<=9;c++)
//			{
//			i=100*a+10*b+c+100*c+10*b+a;
//			if(i==1333)
//		printf("a=%d,b=%d,c=%d\n",a,b,c);	
//			}
//	return 0;
//}



//46. N是4位数，乘9后刚好是其的反序数，求N的值。
//#include<stdio.h>
//#include<math.h>
//#include<stdlib.h>
//int  fanxu(int a);
// main()
// {
//	 int N,M;
//	 for(N=1000;N<=10000;N++)
//	 {
//	 int b=0;
//	 if(fanxu(N)==N*9)
//		 printf("%d\n",N);
//	 }
//	 system("pause");
// }
// int fanxu(int a)
// {
// int i;
// int c=0,b;
// for(i=3;i>=0;i--)
// {
//	b=a%10;
//	c+=b*pow(10,(double)i);
//	a=a/10;
// }
// return c;
 }
