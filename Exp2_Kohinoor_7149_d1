#include <iostream>

using namespace std;

bool isValid(int number) {
    return number % 8 == 0;
}

int main() {
    int number;
    int count = 0;

    while (true) {
        cout << "Enter the number: ";
        cin >> number;

        if (isValid(number)) {
            count++;
        } else {
            break;
        }
    }

    cout << "Total " << count << " numbers are valid numbers." << endl;

    return 0;
}

 32 changes: 32 additions & 0 deletions32  
exp2_7151_Krishna_d1.cpp
@@ -0,0 +1,32 @@
#include <iostream>

using namespace std;

int sumOfSeries(int n) {
    int sum = 0;
    int term_sum = 0;

    for (int i = 1; i <= n; i++) {
        term_sum += i;
        sum += term_sum;
    }

    return sum;
}

int main() {
    int n;
    cout << "Enter a positive integer (n): ";
    cin >> n;

    if (n <= 0) {
        cout << "Please enter a positive integer.";
        return 1;
    }

    int seriesSum = sumOfSeries(n);
    cout << "Sum of series for n = " << n << " is: " << seriesSum << endl;

    return 0;
}
