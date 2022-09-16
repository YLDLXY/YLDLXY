- 👋 Hi, I’m @YLDLXY
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
YLDLXY/YLDLXY is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


int main()
{
	int a = 0;
	int b = 0;
	scanf_s("%d %d", &a,&b);
	int c =	a / 100 * 60 + a % 100 + b;
	printf("再过%d分钟后\n此时的时间为%d点%d分",b,c/60,c%60);
	return 0;
}
