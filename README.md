- 👋 Hi, I’m @longlong345
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
longlong345/longlong345 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <iostream>
#include <array>
using namespace std;

int linearSearch(int arr[], int target, int n) 
{
    for( int i = 0; i < n; i++ ) {
        if ( arr[i] == target) {
            return i;
        }
    }
    return -1;
}

int main() 
{
    int arr[] = {13, 42, 41, 61, 26};
    int target = 422;
    int n = sizeof(arr)/sizeof(a[0]);
    int res = linearSearch(arr, target, n);    
    cout << "The result of linear search = " << res << endl;
    return 0;
}
