
#include <stdio.h>

int main()
{
    int n, i, top = -1;

    printf("Enter number of days: ");
    scanf("%d", &n);

    if(n <= 0)
    {
        printf("Invalid number of days.\n");
        return 1;
    }

    int price[n], span[n], stack[n];

    printf("Enter stock prices:\n");

    for(i = 0; i < n; i++)
    {
        scanf("%d", &price[i]);
    }

    // Calculate stock span using stack
    for(i = 0; i < n; i++)
    {
        while(top != -1 &&
              price[stack[top]] <= price[i])
        {
            top--;
        }

        if(top == -1)
        {
            span[i] = i + 1;
        }
        else
        {
            span[i] = i - stack[top];
        }

        stack[++top] = i;
    }

    // Display results
    printf("\n");
    printf("%-10s %-12s %-10s\n",
           "Day", "Price", "Span");

    printf("--------------------------------\n");

    for(i = 0; i < n; i++)
    {
        printf("%-10d %-12d %-10d\n",
               i + 1, price[i], span[i]);
    }

    return 0;
}
