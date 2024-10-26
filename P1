#include <iostream>
using namespace std;

class SwapNumbers {
    int a, b;
public:
    SwapNumbers(int x, int y) {
        a = x;
        b = y;
        cout << "Before swapping: a = " << a << ", b = " << b << endl;
        swap();
    }

    void swap() {
        int temp = a;
        a = b;
        b = temp;
        cout << "After swapping: a = " << a << ", b = " << b << endl;
    }
};

int main() {
    SwapNumbers obj(5, 10);
    return 0;
}
