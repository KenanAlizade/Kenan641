# include <iostream>
using namespace std;

int main() {
    int n, num, sum = 0;

    cout << "Neçə ədəd daxil etmək istədiyinizi qeyd edin: ";
    cin >> n;

    for(int i = 0; i < n; i++) {
        cout << "Ədəd daxil edin: ";
        cin >> num;

        if(num % 2 == 0) {
            sum += num;
        }
    }

    cout << "Cüt ədədlərin cəmi: " << sum << endl;

    return 0;
}
