#include <iostream>
using namespace std;

double ucgenAlani(double taban, double yukseklik) {
    return (taban * yukseklik) / 2.0;
}

int main() {
    double taban, yukseklik;
    cout << "Tabani giriniz: ";
    cin >> taban;
    cout << "Yuksekligi giriniz: ";
    cin >> yukseklik;

    cout << "Ucgenin alani: " << ucgenAlani(taban, yukseklik) << endl;
    return 0;
}
