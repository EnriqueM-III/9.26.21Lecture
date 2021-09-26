# 9.27.21Lecture
9.27.2021 Lecture. Slides 24-27

// START HERE 9.26.2021 
// ODD AND EVEN

#include <iostream>
using namespace std;

int main() {
    int userNumber;

    cout << "Enter a number and I'll see if it's an odd or an even number! \n";
    cin >> userNumber;

    if (userNumber % 2 == 0)
        cout << "The number you typed, " << userNumber << ". is an even number!";
    else
        cout << "Looks like the number, " << userNumber << ". is an odd number!";

    return 0;
}
  
  
