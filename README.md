#include<stdio.h>
int main()
{
	int n, s = 0;
	printf("연선할 내용 입력하세요（예:-12 +35）:\n");
	while (1)
	{
		scanf_s("%d", &n);
		s += n;
		if (getchar() == '\n')break;
	}
	printf("합은:%d\n", s);
	return 0;
}
***********************
*양호신
*
*20195798
***********************