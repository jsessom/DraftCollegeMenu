# DraftCollegeMenu
Program for Students to select their major at a university.
#include <iostream>
#include <string>
#include <math.h>
#include <iomanip>

using namespace std;
int main()
{
	int selection, numofcourses;
	string major;

	cout << " Menu selection for all majors.  \n";
	cout << " 1. Computer Science. \n";
	cout << " 2. Mathematics. \n";
	cout << " 3. Electronic Engineering. \n";
	cout << " 4. Physics. \n";
	cout << " 5. Science. \n";
	cout << " 6. Undecided. \n";
	cout << "Please enter the number of the major you wish to declare. \n ";
	cin >> selection;

	switch (selection)
	{
	case 1: major = " Computer Science ";
		break;
	case 2: major = " Mathematics ";
		break;
	case 3: major = " Electronic Engineering ";
		break;
	case 4: major = " Physics ";
		break;
	case 5: major = " Science ";
		break;
	case 6: major = " Undecided ";
		break;
	}

	if (selection >= 1 && selection <= 6)
	{
		cout << " How many courses do you wish to take? ";
		cin >> numofcourses;
		cout << " The major you have chosen is " << major << " and the amount of courses you wish to take is "<<numofcourses<< "."<< endl;
		cout << endl;
	}
	else
	{
		cout << " You have made a wrong selection please contact your advisor. " << endl;
		cout << endl;

	}
	
	system("pause");
	return 0;






}
