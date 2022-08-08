- 👋 Hi, I’m @kajalpuniya
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kajalpuniya/kajalpuniya is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>

int main()
{
    int num1, num2;

    /* Input two numbers from user */
    printf("Enter two numbers: ");
    scanf("%d%d", &num1, &num2);

    /* If num1 is maximum */
    if(num1 > num2)
    {
        printf("%d is maximum", num1);        
    }

    /* If num2 is maximum */
    if(num2 > num1)
    {
        printf("%d is maximum", num2);
    }

    /* Additional condition check for equality */
    if(num1 == num2)
    {
        printf("Both are equal");
    }

    return 0;
}
