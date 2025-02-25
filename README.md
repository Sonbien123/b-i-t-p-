# #include <iostream>
using namespace std;

int main() {
    int N;
    
    // Nhập giá trị N
    cout << "Nhap gia tri N: ";
    cin >> N;

    int sum = 0;

    // Lặp qua các số từ 1 đến N và tính tổng
    for (int i = 1; i <= N; ++i) {
        sum += i * 11;
    }

    // In ra kết quả
    cout << "Tong S = " << sum << endl;

    return 0;
}
