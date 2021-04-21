//Jeopardy Eva Mischler, Jake Higgins, Hassan Jafarah.
#include <stdio.h>
#include <stdlib.h>
#include <math.h>

// For Jeopardy
int main()
{
	printf("Welcome to Pitt Jeopardy? Are you ready to play?!");
	printf("1 for yes, 2 for no.");
	int yesNo;
	scanf("%c"&yesNo);
	switch (yesNo)
	{
		case 1:
		printf("Wonderful! Please continue to the next step.");
		break 
		case 2:
		printf("That's sad. Please reconsider);
		break
		default:
		printf("You didn't say yes or no. Just a random number.");
	}
	return 0;
}
