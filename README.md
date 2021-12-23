# continue-break
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	int a = 0;
	while (a <= 10)
	{
		if (a == 6)
			continue;
		printf("%d", a);
		a++;
	}
	return 0;
}
//int main()
//{
//	int a=1;
//	while (a <=20)
//	{
//		if (a == 15)
//			break;
//		printf("%d", a);
//		a++;
//	}
//	return 0;
//}
