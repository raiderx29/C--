#include <iostream>
using namespace std;

#include <iostream>
using namespace std;

int main()
{
    int userIn;
    cout << "Enter a number between 0 and 20: " << endl;
    cin >> userIn;
    while(!((userIn >= 0) && (userIn <= 20)))
    {
       cout << "Wrong Input!" << endl;
       cin >> userIn;
    }
    cout << "N+17 = " << (userIn + 17) << endl;

return 0;
}
