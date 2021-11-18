# Labpy03
# Indira Rully 312110354
## Latihan1.py
SOAL

• Tampilkan n bilangan acak yang lebih kecil dari 0.5

• Nilai n pada saat runtime

• Anda bisa menggunakan while atau for untuk menyelesaikannya

• Gunakan fungsi random () yang dapat di'import terlebih dahulu

Berikut flowchartnya
![img](Screenshot/ss1.png)

Dan ini programnya
![img](Screenshot/ss2.png)

### Berikut penjelasan dari program diatas

print ('Masukkan nilai N: 5')

import random

jumlah = 5

a = 0

for x in range(jumlah):

i = random.uniform(.0,.5)

a+=1

print('data ke:',a,'==>', i)

print ('selesai')

Ini hasilnya
![img](Screenshot/ss3.png)

"print" : berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.

"import" : fungsi lanjut yang dipanggil oleh statement import.

"random" : untuk menentukan suatu pilihan.

"range" : merupakan fungsi yang menghasilkan list. Fungsi ini akan menciptakan sebuah list baru dengan rentang nilai tertentu.

"uniform": digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y.

## Latihan2.py
SOAL

• Buat program untuk menampilkan bilangan terbesar dari n buah data yang di'inputkan

• Dan masukkan angka nol untuk berhenti

Berikut flowchartnya
![img](Screenshot/ss4.png)

Dan ini programnya
![img](Screenshot/ss5.png)

### Berikut penjelas Latihan2.py

max=0

while True:

a=int(input('Masukkan bilangan='))

if max < a:

max = a

if a==0:

break

print('Bilangan terbesarnya adalah',max)

"max" : fungsi bulid-in untuk mencari nilai tertinggi. Fungsi ini dapat diberikan sebuah parameter berupa angka.

"while" : disebut uncounted loop (perulangan yang tak terhitung), untuk perulangan yang memiliki syarat dan tidak tentu berapa banyak perulangannya.

"int" : berfungsi mengkonversi bilangan maupun string angka menjadi bilangan bulat (integer).

"if" = Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu.

"input" : masukan yang kita berikan ke program.

"break" : fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai.

"print" : berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.

## Program1.py
SOAL

•Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya Dengan modal awal 100 juta

•Pada bulan pertama dan kedua belum mendapatkan laba

•Pada bulan ketiga baru mulai mendapatkan laba sebesar 1%

•Pada bulan kelima pendapatan meningkat 5%

•Selanjutnya pada bulan ke-8 mengalami penurunan keuntungan sebesar 2%

•Sehingga laba menjadi 3%

•Hitung total keuntungan selama 8 bulan berjalan usahanya

Berikut flowchartnya
![img](Screenshot/ss6.png)

Dan ini programnya
![img](Screenshot/ss7.png)

### Berikut penjelasan dari Program1.py

•masukkan nilai a

•gunakan for untuk perulangan dari 1 sampai 8.Perulangan for disebut counted loop (perulangan yang terhitung)

•lalu gunakan if pertama untuk menentukan laba bulan ke 1 dan ke 2.masukan variabel (b) kalikan nilai (a) dengan data bulan 1 dan 2. cetak (x) dan (b)

•lalu gunakan if kedua untuk menentukan laba bulan ke 3 dan ke 4.masukan variabel (b) kalikan nilai (a) dengan data bulan 3 dan 4. cetak (x) dan (c)

•lalu gunakan if ketiga untuk menentukan laba bulan ke 5 sampai ke 7.masukan variabel (b) kalikan nilai (a) dengan data bulan 5 sampai 7. cetak (x) dan (d)

•lalu gunakan if keempat untuk menentukan laba bulan ke 8.masukan variabel (b) kalikan nilai (a) dengan data bulan 8. cetak (x) dan (e)

•total keseluruhan

•print total
