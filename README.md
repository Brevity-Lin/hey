//hey
#include<stdio.h>
#define d  8
int main ()
{
    enum weekday {sun=0, mon, tue, wed, thu, fri, sat } day;
	int k;
	printf("请输入星期数(0-7):");
	scanf("%d",&k);
	//day=(enum weekday)k;
	switch(k)
	{
	case mon:
	case tue:
	case wed:
	case thu:
	case fri:     printf("今天要上班\n");  break;

	case sun:
	case sat:      printf("今天不上班\n");  break;

	default:  printf("输入有误！\n");  break;



	}

	printf("%d",d);
    //return 0;



}


//刚开始学习使用
