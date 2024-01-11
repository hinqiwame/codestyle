```c
// includes at the top (default).
#include <stdio.h> 

// not using snakecase or whatever.
// all the names for variables, functions, typedefs, structs, etc. should just look like "varname", "funcname".

int addtwonumbers(int n1, int n2)
{ // the function brackets should open on the NEXT line after declaring the function.
	return n1 + n2;
}

// this will be just the example driver code
int main()
{
	// declare the variables first
	int two = 2;
	int thirtyfive = 35;
	int sum = addtwonumbers(two, thirtyfive);

	printf("%d\n", sum);

	// now about the conditions; this is the way the should look:
	if (sum > 100) { // the condition brackets should open on the SAME line after declaring a condition.
		printf("The value of the 'sum' variable is more than 100.\n");
	} else { // better to keep the else on the SAME line after closing the first "if" condition, just to show the logic kinda.
		printf("The value of the 'sum' variable is less than 100.\n");
	}

	return 0;
}
```
