#include <stdio.h>
int main () {
	int start, end, broj, state;
	scanf("%d %d", &start, &end);
	for(; start<=end; start++) {
		broj = start;
		state = 1;
		while(broj) {
			if ((broj%10)%2) {
				state = 0;
				break;
			}
			broj/=10;
		}
		if (state) {
		break; }
	}
	if (state) {
		printf("%d\n", start);
	} else {
		printf("NE");
	}
	return 0;
}
