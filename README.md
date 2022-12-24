## Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Pemrograman
<br> Nama		: ALIF FIRMANSYAH PUTRA
<br>NIM			: 1227050016
<br>Jurusan		: Teknik Informatika UIN Sunan Gunung Djati Bandung 

## Deskripsi Umum
Pada program kali ini ada dua program yang akan di tampilkan pada halaman ini, Yaitu program mencari deret dan program mengubah kolom dan baris matriks.

Program pertama, program ini dibuat untuk mengubah atau menukar baris dan kolom pad amtriks.
Langkah awalnya yaitu user menginputkan berapa banyak baris pada array, lalu input nilai satu persatu pada matriks, Lalu niilai pada array tersebut di tampilkan sesuuai dengan aturan matriks, Lalu di tampilkan juga kebalikan dari kolom dan baris matriks tersebut

Program kedua, program ini dibuat menggunakan konsep Multi Dimmensional Array (MDA) yang mana program pertama memiliki fungsi untuk melakukan pencarian nilai deret yang tidak habis dibagi dengan 3,5,7
langkah awalnya yaitu user menginputkan banyak baris deret pada kolom array, lalu input nilai pada array, kemudian data yang telah diinput akan ditampilkan sesusai dengan konsep deret yang tidak habis dibagi 3,5,7.  

## Source Code
Source Code Soal No.1

		#include <iostream>
		#include <conio.h>
		using namespace std;

		int main(){
		  int i, j, b, k, matriks[10][10], transpose[10][10];

		  cout << "NAMA ALIF FIRMANSYAH PUTRA \n" << "NIM: 1227050033 \n";
		  cout << "MENGUBAH KOLOM DAN BARIS PADA MATRIKS \n";
		  cout << "==================================================\n";

		  cout << "Masukkan jumlah baris matriks: ";
		  cin >> b;
		  cout << "Masukkan jumlah kolom matriks: ";
		  cin >> k;
		  cout << endl;

		  cout << "Masukkan elemen matriks \n";
		  for (i = 0; i < b; i++) {
		    for (j = 0; j < k; j++) {
		      cout << "Nilai Baris " << i+1 << " Kolom " << j+1 << " = " ;
			  cin  >> matriks[i][j];
		    }
		  }
		  cout << "\n";

		  cout << "Matriks Awal : \n";
		  for (i = 0; i < b; i++){
		    for (j = 0; j < k; j++){
		      cout << matriks[i][j] << "\t";
		    }
		    cout << endl;
		  }


		  for (i = 0; i < b; i++){
		    for (j = 0; j < k; j++){
		      transpose[j][i] = matriks[i][j];
		    }
		  }

		  cout << "Hasil Transpose Matriks: \n";
		  for (i = 0; i < k; i++){
		    for (j = 0; j < b; j++){
		      cout << transpose[i][j] << "\t";
		    }
		    cout << endl;
		  }
			getch();
		}
Source Code Soal No.2

		#include <iostream>
		#include <conio.h>
		using namespace std;

		int main(){
		  int i, j, b, k, matriks[10][10], transpose[10][10];

		  cout << "NAMA ALIF FIRMANSYAH PUTRA \n" << "NIM: 1227050033 \n";
		  cout << "MENGUBAH KOLOM DAN BARIS PADA MATRIKS \n";
		  cout << "==================================================\n";

		  cout << "Masukkan jumlah baris matriks: ";
		  cin >> b;
		  cout << "Masukkan jumlah kolom matriks: ";
		  cin >> k;
		  cout << endl;

		  cout << "Masukkan elemen matriks \n";
		  for (i = 0; i < b; i++) {
		    for (j = 0; j < k; j++) {
		      cout << "Nilai Baris " << i+1 << " Kolom " << j+1 << " = " ;
			  cin  >> matriks[i][j];
		    }
		  }
		  cout << "\n";

		  cout << "Matriks Awal : \n";
		  for (i = 0; i < b; i++){
		    for (j = 0; j < k; j++){
		      cout << matriks[i][j] << "\t";
		    }
		    cout << endl;
		  }


		  for (i = 0; i < b; i++){
		    for (j = 0; j < k; j++){
		      transpose[j][i] = matriks[i][j];
		    }
		  }

		  cout << "Hasil Transpose Matriks: \n";
		  for (i = 0; i < k; i++){
		    for (j = 0; j < b; j++){
		      cout << transpose[i][j] << "\t";
		    }
		    cout << endl;
		  }
			getch();
		}
## Output
- Soal No.1
 ![UAS 1 ALIF FIRMANSYAH](https://user-images.githubusercontent.com/121073257/209417643-bba9283f-5943-4073-b6d1-9f6f3e013c00.png)
 
- Soal No.2 
 <img width="597" alt="![UAS 2 ALIF FIRMANSYAH](https://user-images.githubusercontent.com/121073257/209417407-24eeae6f-feda-474d-91c9-20289be32ac6.png)">
