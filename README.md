# LAPORAN PRAKTIKUM

## MEMBUAT REPOSITORY

### Step 1 : Pembuatan Akun Github
Buatlah akun pada github.com jika belum memilikinya,
Jika sudah punya/selesai membuat maka tampilannya akan seperti ini pada menu PROFIL :
![Gambar1](ssgit.png)

### Step 2 : Buat file Repository
Setelah itu kembali ke HOME dan tekan NEW :
![Gambar1](new.png)

setelah ditekan maka tampilannya akan seperti di bawah, setting Public pada 2 pilihan pada gambar :
![Gambar](public.png)

Tekan Create Repository :
![Gambar1](creat.png)

### Step 3 : Penginstalan Git Tools
Download terlebih dahulu Git Tools dengan mengetik git=scm dipencarian google, lalu tekan Download for Windows :
![Gambar1](gitscm.png)

Setelah itu tekan "Click here to download" :
![Gambar1](download.png)

Setelah didownload, kita masuk ke proses Penginstalan tekan apk git tools yang sudah didownload lalu klik next terus hingga tampilannya seperti ini,
lalu tekan instal :
![Gambar1](instal.png)

Tunggu hingga proses Penginstalan selesai hingga tampilannya seperti di bawah lalu tekan finish :
![Gambar1](finish.png)

### Step 4 : Pengoperasian Git Tools
Setelah clear Penginstalan maka tampilannya akan seperti digambar :
![Gambar1](pwd.png)

Kode awal yang di buat berupa 'pwd' untuk memeriksa data file
Sebelum masuk langkah selanjutnya copy code github kamu dikolom CODE :
![Gambar1](code.png)

Lalu kembali ke Git Tools dan lanjutkan dengan 'git clone pastelinkgithub'
setelahnya cari file README.md pada file web1 :
![Gambar1](readme.png)

Lalu buka file README.md dengan VS Code maka tampilannya seperti ini :
![Gambar1](vsc.png)

Lalu buat file baru :
![Gambar1](newfile.png)

Ganti menjadi python :
![Gambar1](py.png)

Dan save pada file web1, ganti nama sesuai kemauan :
![gambar1](sv.png)

Kembali ke Git Tools, ketik 'git add web1/' untuk menambahkan, lalu commit dengan mengetik 'git commit -m (komentar bebas)', jika sudah ketik lagi 'git push -u origin main' maka konten yang kita tambahkan pada file web1 sudah terupdate digithub

## MEMBUAT CODE PROGRAM FLOWCHART DENGAN PYTHON

### Step 1 :
Pada langkah pembuatan repository kita sudah membuat file baru berupa python, sekarang kita akan coba membuat code program flowchart menggunakan python. Buat code program inputkan bilangan dengan menggunakan integer untuk memasukan bilangan bulat :
![Gambar1](bilangan.png)

Dilanjutkan dengan memasukan if, elif dan else untuk membandingkan dari 3 bilangan yang sudah di inputkan. Penjelasannya :

Jika Bilangan1 lebih besar atau sama dengan >= Bilangan2  dan Bilangan1 lebih besar atau sama dengan >= Bilangan3 maka yang terbesar Bilangan1

Kemungkinan lain Bilangan2 lebih besar atau sama dengan >= Bilangan1  dan Bilangan2 lebih besar atau sama dengan >= Bilangan3 maka yang terbesar Bilangan2

Selain dari itu maka yang terbesar Bilangan3
![Gambar1](else.png)

Setelah code proses sudah selesai maka masukan output untuk di tampilkan, printah 'print' digunakan untuk output :
![Gambar1](print.png)

Selanjutnya kita coba run code program dan inputkan bilangan :
Bilangan1 = 15
Bilangan2 = 3
Bilangan3 = 11
maka akan ditampilan output terbesar dari 3 bilangan yang sudah di input : Bilangan1 = 15
![Gambar1](hasil.png)

## Deskripsi Program
Program ini menerima tiga input bilangan dari pengguna dan menentukan bilangan terbesar dari ketiga bilangan tersebut. Program ini menggunakan kondisi if-elif untuk membandingkan bilangan-bilangan yang dimasukkan oleh pengguna.

### Algoritma:
1.  Program meminta pengguna memasukkan tiga bilangan.
2. Program kemudian membandingkan ketiga bilangan tersebut menggunakan if-elif.
3. Bilangan yang paling besar akan ditampilkan sebagai hasil.

## Flowchart Program
(sertakan gambar flowchart di sini)

## Hasil Eksekusi Program
(sertakan screenshot hasil eksekusi program di sini)