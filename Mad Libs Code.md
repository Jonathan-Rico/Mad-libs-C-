// Homework 1.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include <string>
using namespace std;

int _tmain(int argc, _TCHAR* argv[])
{	
	std:: cout << "Hello, Welcome to the Mad Lib program.\nFollow the instructions to create a small story .\n";

	string string1;
	std:: cout << "Type in a place (not a place with a proper name) and press enter to continue.\n";
	std:: cin >> string1;

	string string2;
	std:: cout << "Type in a adverb and press enter to continue.\n";
	std:: cin >> string2;

	string string3;
	std:: cout << "Type in a the name of a high level programming computer language \nand press enter to continue.\n";
	std:: cin >> string3;

	string string4;
	std:: cout << "Type in a name and press enter to continue.\n";
	std:: cin >> string4;

	string string5;
	std:: cout << "Type in an adjective describing speed and press enter to continue.\n";
	std:: cin >> string5;

	string string6;
	std:: cout << "Type in an infinitive verb to finish the story .\n";
	std:: cin >> string6;


	std:: cout << "There once was a man who lived in a "<< string1 << ".\n"<< "He always worked on computer programs " << string2 << " using " << string3 << " .\n" << "His name was " << string4 << ". " << "His computer was very " << string5 << ".\n" << "After finishing his program, he began to "<< string6 << ".\n";

}

