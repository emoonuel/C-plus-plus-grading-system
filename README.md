# C-plus-plus-grading-system
grading system in C++


//GRADES

#include <iostream>

int main()
{

char grade;

std::cout << "What letter grade?: ";
std::cin >> grade;

switch (grade){
    case 'A':
    std::cout << "EXCELLENT!";
    break;
    case 'B':
    std::cout << " You did good";
    break;
    case 'C': 
    std::cout << "You did ok";
    break;
    case 'D':
    std::cout << "You did not do good";
    break;
    case 'F':
    std::cout << "You failed.";
    break;
    default:
    std::cout << "Please only enter in a letter grade (A-F)";


}



return 0;
}

// merit ©
// You must first install all appropriate C++ extensions in VS code
// Other than that enjoy!
