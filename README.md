# Function_Parameters_PowerOf
C++ Program

    #include <iostream>
    #include <cmath>
    using namespace std;
    void TwoPower (int number, int power){
        cout << " 2 to the power of " << number << " is " << power << endl;
    }
    int main() {
        int n;
        for(int n = 1; n <= 10; n++){
        TwoPower(n, pow(2,n));
    }
    }
