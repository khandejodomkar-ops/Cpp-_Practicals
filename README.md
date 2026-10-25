#include <iostream>
using namespace std;

int main() {
    int age;
    double marks;
    char grade;
    bool passed;

    const int bonus = 5;

    cout <<" Enter your age :";
    cin >> age;

    cout <<" Enter your marks :";
    cin >> marks;

    cout <<" Enter your grade(A/B/C/D) :";
    cin >> grade;

    double finalmarks = marks + bonus;
    
    passed = (finalmarks >= 40 && age >= 18);

    cout << "\n--- Student Details ---\n";
    cout << "Age: " << age << endl;
    cout << "Marks: " << marks << endl;
    cout << "Grade: " << grade << endl;
    cout << "Bonus: " << bonus << endl;
    cout << "Final Marks: " << finalmarks << endl;
    cout << "Passed: " << (passed ? "Yes" : "No") << endl;
return 0;
}
