# My_little_corner
Welcome to my repository!

# Мой код:
```C++
#include <iostream>
#include <string>
using namespace std;
int main() {
	string amax = "0";
	string a;
	cin >> a;
	for(int i = 1;i < a.size()-1; i++){
		if((a[i-1] == a[i]) && (a[i] == a[i+1])){
			string c;
			c = a[i];
			if(c > amax){
				amax = c;
			}
		}
	}
	if (amax == "0"){
		cout << "";
	}
	else{
		cout << amax << amax << amax;
	}
	system("pause");
	return 0;
}
```

