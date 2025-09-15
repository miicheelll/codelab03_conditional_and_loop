# codelab03_conditional_and_loop

Michelle Dorani Shiba/18/2341720113

Praktikum 1
- Langkah 2 :
  
  ![alt text](img/Code_Prak1_Lngkh2.jpg?raw=true)
  ![alt text](img/Prak1_Lngkh2.jpg?raw=true)

  Kode tidak bisa dijalankan karena ada kesalahan sintaks:
  - Di Dart, keyword harus huruf kecil: if, else if, else.
  
- Langkah 3 :
  
  ![alt text](img/Code_Prak1_Lngkh3.jpg?raw=true)
  ![alt text](img/Prak1_Lngkh3.jpg?raw=true)
  
  Kode tidak bisa jalan karena:
  - Penulisan keyword dengan kapital.
  - Pengulangan deklarasi test.
  - Tipe data salah di kondisi if (test) error, karena test bertipe String, bukan bool. Dart hanya menerima true/false (boolean) di dalam if.
  
- Perbaikan :
  
  ![alt text](img/Code_Prak1_Perbaikan.jpg?raw=true)
  ![alt text](img/Prak1_Perbaikan.jpg?raw=true)
  
  Perbaikan yang dilakukan:
  - Mengganti penulisan If, Else If, Else menjadi if, else if, else.
  - Memisahkan variabel agar tidak redeclare (test = test2)
  - Membandingkan string secara eksplisit (if (test2 == "true")).

  Hasil akhir program:
  - Mencetak Test2 lalu Test2 again.
  - Mencetak Kebenaran.

Praktikum 2
- Langkah 2 :
  
  ![alt text](img/Code_Prak2_Lngkh2.jpg?raw=true)
  ![alt text](img/Prak2_Lngkh2.jpg?raw=true)
  
  Kode tidak bisa jalan karena:
  - Variabel counter belum pernah dideklarasikan atau diberi nilai awal (misalnya int counter = 0;).
  - Tanpa inisialisasi, program akan error saat kompilasi: “Undefined name 'counter'”.
  
- Langkah 3 :
  
  ![alt text](img/Code_Prak2_Lngkh3.jpg?raw=true)
  ![alt text](img/Prak2_Lngkh3.jpg?raw=true)
  
  Kode tidak bisa jalan karena:
  - Variabel counter belum pernah dideklarasikan (misalnya int counter = 0;).
  
- Perbaikan :
  
  ![alt text](img/Code_Prak2_Perbaikan.jpg?raw=true)
  ![alt text](img/Prak2_PerbaikanA.jpg?raw=true)
  ![alt text](img/Prak2_PerbaikanB.jpg?raw=true)
  
  Perbaikan yang dilakukan:
  - Menambahkan deklarasi variabel int counter = 0; agar counter dikenali.
  - Menutup blok main dengan tanda kurung kurawal } yang benar.
  - Menjaga konsistensi indentasi agar kode lebih rapi dan mudah dibaca.

  Hasil akhir program:
  - Bagian while mencetak angka 0 sampai 32.
  - Bagian do...while melanjutkan mencetak angka 33 sampai 76.
  - Jadi total output adalah angka 0 sampai 76 berurutan.

Praktikum 3
- Langkah 2 :
  
  ![alt text](img/Code_Prak3_Lngkh2.jpg?raw=true)
  ![alt text](img/Prak3_Lngkh2.jpg?raw=true)
  
  Kode tidak jalan karena:
  - Variabel Index belum pernah dideklarasikan (int index = ...;).
  - Penulisan Index dan index tidak konsisten (huruf besar/kecil beda, dianggap variabel berbeda).
  - Bagian for (Index = 10; index < 27; index) salah, karena index++ harus dipakai, bukan index.
    
- Langkah 3 :
  
  ![alt text](img/Code_Prak3_Lngkh3.jpg?raw=true)
  ![alt text](img/Prak3_Lngkh3.jpg?raw=true)
  
  Kode tidak jalan karena:
  - Variabel index/Index belum pernah dideklarasikan (int index = ...; wajib).
  - Penulisan If, Else If dengan huruf besar tidak valid di Dart (harus if, else if).
  - Pada for (...), bagian increment hanya index tanpa ++, jadi tidak ada perubahan nilai → infinite loop.
  - Inconsistent: kadang pakai Index, kadang index → dianggap variabel berbeda.
  
- Perbaikan :
  
  ![alt text](img/Code_Prak3_Perbaikan.jpg?raw=true)
  ![alt text](img/Prak3_Perbaikan.jpg?raw=true)
  
  Perbaikan yang dilakukan:
  - Deklarasi variabel → int index = 10; ditambahkan di dalam for.
  - Penulisan Index/index → diseragamkan jadi index (case-sensitive).
  - Increment → index++ ditulis dengan benar, bukan sekadar index.
  - Keyword → If dan Else If diganti jadi if dan else if (sesuai sintaks Dart).

  Hasil akhir program:
  - Loop mencetak angka 10 sampai 21.
  - Saat index == 21, perulangan berhenti karena break.
  - continue selalu aktif, jadi baris kedua print(index); tidak pernah dijalankan.

Tugas Praktikum
- Program bil. prima
  
  ![alt text](img/Code_TugasPrak.jpg?raw=true)
  ![alt text](img/TugasPrak_A.jpg?raw=true)
  ![alt text](img/TugasPrak_B.jpg?raw=true)

  Penjelasan:
  - for digunakan untuk mengulang dari 0 sampai 201.
  - Fungsi isPrima() mengecek apakah n bilangan prima.
  - Jika isPrima(i) bernilai true, program mencetak angka tersebut bersama nama lengkap dan NIM.


