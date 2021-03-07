#include <iostream>
#include <string>
using namespace std;

int main() {
	char word[20];
	int i, length;
	int flag = 0;

	cout << "Enter word: ", cin >> word;

	length = strlen(word);

	for (i = 0; i < length; i++) {
		if (word[i] == word[length - i - 1]) {
			flag = 1;
			break;
		}
	}

	if (flag) {
		cout << word << " is not a palindrome." << endl;
	}
	else {
		cout << word << " is a palindrome." << endl;
	}
	system("pause");
	return 0;
}
