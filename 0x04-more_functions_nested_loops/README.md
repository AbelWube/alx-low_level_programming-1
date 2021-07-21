0x04. C - More functions, more nested loops

Question #0
What is the output of the following piece of code?

int i;

for (i = 48; i < 58; i++)
{
    printf("%c", i);
}

0123456789

Question #1
What is the output of the following piece of code?

int i;

i = 0;
while (i < 10)
{
    printf("%d", i % 2);
    i++;
}

0101010101

Question #2
What is the output of the following piece of code?

int i;

for (i = 0; i < 10; i++)
{
    printf("%d", i * 2);
}

024681012141618

Question #3
What is the output of the following piece of code?

int i;

i = 0;
while (i < 10)
{
    i++;
    printf("%d", i / 2);
}

0112233445

Question #4
What is the output of the following piece of code?

int i;

i = -9;
while (i < 0)
{
    printf("%d", -i);
    i++;
}

987654321

Question #5
What is the output of the following piece of code?

int i;

i = 9;
while (i--)
{
    printf("%d", i);
}

876543210

Question #6
What is the output of the following piece of code?

int i;

i = 9;
while (--i)
{
    printf("%d", i);
}

87654321

Question #7
What is the return value of the following function?

int some_function(void)
{
    printf("%d", 12);
    return (98);
}

98

Question #8
What is the return value of the following function?

int some_function(void)
{
    int i;

    for (i = 0; i < 10; i++)
    {
        printf("%d", i);
    }
    return(i);
}

10
