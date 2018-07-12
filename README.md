#include "stdafx.h"
#include <iostream>

void sumTo(int x)
{
	int total{ 0 };
	for (int count{ 0 }; count <= x; ++count)
		total += count;
		std::cout << total << '\n';
}

int main()
{
	std::cout << "Enter an interger :";
	int x;
	std::cin >> x;

	sumTo(x);


    return 0;
}

