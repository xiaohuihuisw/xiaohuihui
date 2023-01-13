# [test_2_05.zip](https://github.com/xiaohuihuisw/-/files/10411891/test_2_05.zip)

[test_2_23.zip](https://github.com/xiaohuihuisw/-/files/10411926/test_2_23.zip)

#include<stdio.h>
#include<string.h>

int main()
{
	int count = 0;
	int year = 0;
	for (year = 1000; year <= 2000; year++)
	{
		if (year % 4 == 0 && year % 100 != 0)
		{
			printf(" %d", year);
			count++;
		}
		 else if (year % 400 == 0)
		{
			printf(" %d", year);
			count++;
		}
	}
	printf("\ncount= %d\n", count);
	return 0;

}



//int main()
//{    
//	int i = 0;
//	for (i = 0; i <= 100; i++)
//	{
//		if (i % 3 == 0)
//			printf(" %d ", i);
//
//	}
//	return 0;
// }
//int main()
//{
//    int a = 0;
//    int b = 0;
//    int c = 0;
//    scanf_s("%d%d%d", &a, &b, &c);
//    if (a < b)
//    {
//        int tmp = a;
//        a = b;
//        b = tmp;
//    
//    }
//    if (a < c)
//    {
//        int tmp = a;
//        a = c;
//        c = tmp;
//
//    }
//    printf("%d,%d,%d", a, b, c);
//    return 0;
//}
