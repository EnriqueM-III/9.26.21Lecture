# 9.27.21Lecture
9.27.2021 Lecture. Slides 24-27


  
  

// ODD AND EVEN
/*
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
*/

//NUMBER CHECKER
/*
#include <iostream>;
using namespace std;

int main() {
    int userNumber;

    cout << "I'll identify is the number you write is either a zero, positive or negative number. Write one down: \n";
        cin >> userNumber;

        if (userNumber > 0) {
            cout << "The number you entered is greater than 0. It's a positive number!";
        }
        else if (userNumber < 0) {
            cout << "The number you entered is less than 0. It's a negative number!";
        }

        else {
            cout << "That is the number zero.";
        }

        return 0;

}
*/

/*
//SALE OR PROFIT
#include <iostream>
using namespace std; 

    int main()
    {

        int purchasePrice, salePrice, prof;

        cout << "Insert Purchase Price: ";
        cin >> purchasePrice;
        cout << "Insert Sale Price: ";
        cin >> salePrice;

        prof = (purchasePrice - salePrice);


        if (prof > 0) {
            cout << "You profited " << prof;
        }

        else if (prof < 0) {
            cout << "You loss by " << prof;
        }
        else {
            cout << "No profit nor loss. Neutral result";
        }

        return 0;

}
    */

// SHAPES
/*
#include <iostream>
using namespace std;

int main()

{
    int sides;
    string shape;
    cout << "I'll name the shape based on what number you write down. Only up to 10 though. \n";

        cin >> sides;

        if (sides <= 2) {
            cout << "There are no shapes with less than 2 sides. Try again!";
        }
        else if (sides == 3) {
            cout << "This is a Triangle!";
        }
        else if (sides == 4) {
            cout << "This is a Square!";

        }
        else if (sides == 5) {
            cout << "This is a Pentagon!";

        }
        else if (sides == 6) {
            cout << "This is a Hexagon!";

        }
        else if (sides == 7) {
            cout << "This is a Heptagon!";

        }
        else if (sides == 8) {
            cout << "This is a Octagon!";

        }
        else if (sides == 9) {
            cout << "This is a Nonagon!";

        }
        else if (sides <= 10) {
            cout << "This is a Decagon!";

        }
        else {
            cout << "I told you I can only go up to 10. Next time I might go beyond 10 with efficiency! \n";
        }

        cin.get();
        return 0;

}
*/

/*
//SALE OR PROFIT
#include <iostream>
using namespace std; 

    int main()
    {

        int purchasePrice, salePrice, prof;

        cout << "Insert Purchase Price: ";
        cin >> purchasePrice;
        cout << "Insert Sale Price: ";
        cin >> salePrice;

        prof = (purchasePrice - salePrice);


        if (prof > 0) {
            cout << "You profited " << prof;
        }

        else if (prof < 0) {
            cout << "You loss by " << prof;
        }
        else {
            cout << "No profit nor loss. Neutral result";
        }

        return 0;

}
    */

// SHAPES
/*
#include <iostream>
using namespace std;

int main()

{
    int sides;
    string shape;
    cout << "I'll name the shape based on what number you write down. Only up to 10 though. \n";

        cin >> sides;

        if (sides <= 2) {
            cout << "There are no shapes with less than 2 sides. Try again!";
        }
        else if (sides == 3) {
            cout << "This is a Triangle!";
        }
        else if (sides == 4) {
            cout << "This is a Square!";

        }
        else if (sides == 5) {
            cout << "This is a Pentagon!";

        }
        else if (sides == 6) {
            cout << "This is a Hexagon!";

        }
        else if (sides == 7) {
            cout << "This is a Heptagon!";

        }
        else if (sides == 8) {
            cout << "This is a Octagon!";

        }
        else if (sides == 9) {
            cout << "This is a Nonagon!";

        }
        else if (sides <= 10) {
            cout << "This is a Decagon!";

        }
        else {
            cout << "I told you I can only go up to 10. Next time I might go beyond 10 with efficiency! \n";
        }

        cin.get();
        return 0;

}
*/
