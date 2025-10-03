# Program-CPP-Regine-Levana-Xaviera-Al-Subhan_Leda_TLS25

#include <string>
using namespace std;

int main(){
    string mysterious;
    string hasil = "";
    cout << "Kata mysterious: " << mysterious;
    cin >> mysterious;

for(int i = mysterious.size() - 1; i >= 0; i--) {
    if(i > 0 && mysterious[i-1] == '7' && mysterious[i] == '1'){
        hasil;
        i--;
    } else{
        hasil += mysterious[i];
    }
} 
      cout << "Kata baru: " << hasil;
      

return 0;
}
