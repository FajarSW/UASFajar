# UASFajar
# Ujian Akhir Semester 
<br>Mata Kuliah 	:
<br> Nama		:
<br>NIM		:	
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

## Source Code
Soal No. 1
```cpp
#include<iostream>
#include<iomanip>
using namespace std;

int main(){
    
	int arr[100][100], jumlahBaris, jumlahKolom, i, j, baris, kolom;
	
	cout<< "=======================================\n";
	cout<< "Program Mencetak Matrix Transpos\n";
	cout<< "=======================================\n";
	cout<< "Nama  : Fajar Satria Wiguna \n";
	cout<< "Nim   : 1227050042\n";
	cout<< "Kelas : Informatika - A\n\n";

    cout<<"Input jumlah baris: "; cin>>jumlahBaris;
    cout<<"Input jumlah kolom: "; cin>>jumlahKolom;
    cout << endl;

    for(i = 0; i < jumlahBaris; i++){
        for(j = 0; j < jumlahKolom; j++){
            cout << "Baris " <<i+1<<", kolom "<<j+1<< " = ";
            cin >> arr[i][j];
        }
        cout << endl;
    }
    cout << "Hasil matriks: " << endl;

    for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
        cout << setw(3) << arr[i][j] << " ";
    }
    cout << endl;
    }

    baris = jumlahBaris;
    kolom = jumlahKolom;

    jumlahKolom = baris;
    jumlahBaris = kolom;

    cout << "\nUbah kolom jadi baris dan baris jadi kolom: " << endl;

    for(i = 0; i < jumlahBaris ; i++){
    	for(j = 0; j < jumlahKolom; j++){
        cout << setw(3) << arr[j][i] << " ";
    }
    cout << endl;
    }
	return 0;
}
```
Soal No. 2
```cpp
#include <iostream>
#include <iomanip>
using namespace std;
int main(){
    
	int arr[100][100], jumlahBaris, jumlahKolom, i, j, baris, kolom;
	
	cout<< "==============================================\n";
	cout<< "Program Bilangan Yang Habis Dibagi 3, 5, dan 7\n";
	cout<< "==============================================\n";
	cout<< "Nama  : Fajar Satria Wiguna \n";
	cout<< "Nim   : 1227050042\n";
	cout<< "Kelas : Informatika - A\n\n";

    cout<<"Input jumlah baris: "; cin>>jumlahBaris;
    cout<<"Input jumlah kolom: "; cin>>jumlahKolom;
    cout << endl;

    for(i = 0; i < jumlahBaris; i++){
        for(j = 0; j < jumlahKolom; j++){
            cout << "Baris " <<i+1<<", kolom "<<j+1<< " = ";
            cin >> arr[i][j];
        }
        cout << endl;
    }

    cout << "Hasil input nilai : " << endl;

    for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
        cout << setw(3) << arr[i][j] << " ";
    }
    cout << endl;
    }

    cout << "\nHasil bilangan yang habis dibagi 3,5,7 : " << endl;

    for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
        if(arr[i][j] % 3 == 0 || arr[i][j] % 5 == 0 || arr[i][j] % 7 == 0){
        cout << setw(3) << arr[i][j] << " ";
        }
    }
    cout << endl;
    }

    
    cout << endl;
    return 0;
}
```
## Output
