#include <iostream>

using namespace std;

void welcome();

char getYesNo();

void printResponce(char responceToPrint);



int main()

{
	welcome();

	char answer = getYesNo();

	printResponce(answer);




	system("pause");

}

void welcome()

{
	cout << "Welcome! \n";
}

char getYesNo()

{

	cout << "Please answer: y or n. \n";
	char responce;

	cin >> responce;

	return responce;
	
}
void printResponce(char responceToPrint)

{

	cout << "Your answer was:" << responceToPrint << endl;
}
