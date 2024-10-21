# LAPORAN PRAKTIKUM

## MEMBUAT REPOSITORY

### Step 1 : Pembuatan Akun Github
Buatlah akun pada github.com jika belum memilikinya,
Jika sudah punya/selesai membuat maka tampilannya akan seperti ini pada menu PROFIL :
![Gambar1](screenshoot/ssgit.png)

### Step 2 : Buat file Repository
Setelah itu kembali ke HOME dan tekan NEW :
![Gambar1](screenshoot/new.png)

setelah ditekan maka tampilannya akan seperti di bawah, setting Public pada 2 pilihan pada gambar :
![Gambar](screenshoot/public.png)

Tekan Create Repository :
![Gambar1](screenshoot/creat.png)

### Step 3 : Penginstalan Git Tools
Download terlebih dahulu Git Tools dengan mengetik git=scm dipencarian google, lalu tekan Download for Windows :
![Gambar1](screenshoot/gitscm.png)

Setelah itu tekan "Click here to download" :
![Gambar1](screenshoot/download.png)

Setelah didownload, kita masuk ke proses Penginstalan tekan apk git tools yang sudah didownload lalu klik next terus hingga tampilannya seperti ini,
lalu tekan instal :
![Gambar1](screenshoot/instal.png)

Tunggu hingga proses Penginstalan selesai hingga tampilannya seperti di bawah lalu tekan finish :
![Gambar1](screenshoot/finish.png)

### Step 4 : Pengoperasian Git Tools
Setelah clear Penginstalan maka tampilannya akan seperti digambar :
![Gambar1](screenshoot/pwd.png)

Kode awal yang di buat berupa 'pwd' untuk memeriksa data file
Sebelum masuk langkah selanjutnya copy code github kamu dikolom CODE :
![Gambar1](screenshoot/code.png)

Lalu kembali ke Git Tools dan lanjutkan dengan 'git clone pastelinkgithub'
setelahnya cari file README.md pada file web1 :
![Gambar1](screenshoot/readme.png)

Lalu buka file README.md dengan VS Code maka tampilannya seperti ini :
![Gambar1](screenshoot/vsc.png)

Lalu buat file baru :
![Gambar1](screenshoot/newfile.png)

Ganti menjadi python :
![Gambar1](screenshoot/py.png)

Dan save pada file web1, ganti nama sesuai kemauan :
![gambar1](screenshoot/sv.png)

Kembali ke Git Tools, ketik 'git add web1/' untuk menambahkan, lalu commit dengan mengetik 'git commit -m (komentar bebas)', jika sudah ketik lagi 'git push -u origin main' maka konten yang kita tambahkan pada file web1 sudah terupdate digithub

## MEMBUAT CODE PROGRAM FLOWCHART DENGAN PYTHON

### Step 1 :
Pada langkah pembuatan repository kita sudah membuat file baru berupa python, sekarang kita akan coba membuat code program flowchart menggunakan python. Buat code program inputkan bilangan dengan menggunakan integer untuk memasukan bilangan bulat :
![Gambar1](screenshoot/bilangan.png)

### Step 2 :
Dilanjutkan dengan memasukan if, elif dan else untuk membandingkan dari 3 bilangan yang sudah di inputkan. Penjelasannya :

Jika Bilangan1 lebih besar atau sama dengan >= Bilangan2  dan Bilangan1 lebih besar atau sama dengan >= Bilangan3 maka yang terbesar Bilangan1

Kemungkinan lain Bilangan2 lebih besar atau sama dengan >= Bilangan1  dan Bilangan2 lebih besar atau sama dengan >= Bilangan3 maka yang terbesar Bilangan2

Selain dari itu maka yang terbesar Bilangan3
![Gambar1](screenshoot/else.png)

### Step 3 :
Setelah code proses sudah selesai maka masukan output untuk di tampilkan, printah 'print' digunakan untuk output :
![Gambar1](screenshoot/print.png)

### Step 4 :
Selanjutnya kita run code program dan inputkan bilangan :
Bilangan1 = 15
Bilangan2 = 3
Bilangan3 = 11
maka akan ditampilan output terbesar dari 3 bilangan yang sudah di input : Bilangan1 = 15
![Gambar1](screenshoot/hasil.png)

## MEMBUAT FLOWCHART MENENTUKAN TERBESAR DARI 3 BILANGAN

### Step 1 :
Buat start untuk diawalan proses dengan bentuk terminator :

![Gambar1](screenshoot/start.png)

### Step 2 :
Ke langkah selanjutnya masukan Input Bilangan 1, 2, 3 dengan printah 'Read' :

![Gambar1](screenshoot/read.png)

### Step 3 :
Buat lah decision untuk keputusan, jika Bilangan1 >= Bilangan2 YA/TIDAK? :

![Gambar1](screenshoot/if.png)

### Step 4 :
Jika YA maka akan lanjut, jika Bilangan1 >= Bilangan3 YA/TIDAK?. Jika TIDAK maka akan lanjut, jika Bilangan2 >= Bilangan3 YA/TIDAK? :

![Gambar1](screenshoot/yn.png)

### Step 5 :
Masukan Output dengan printah 'Write' :

Jika YA Bilangan1 >= Bilangan3 maka Bilangan1 terbesar
Jika TIDAK BIlangan1 >= Bilangan3 maka Bilangan3 terbesar

Jika YA Bilangan2 >= Bilangan3 maka Bilangan2 terbesar
Jika TIDAK Bilangan2 >= Bilangan3 maka Bilangan3 terbesar

![Gambar1](screenshoot/outputt.png)

### Step 6 :
Buat titik berhenti pada flowchart dengan bentuk Terminator :

![Gambar1](screenshoot/endd.png)

## KESIMPULAN
Penggunaan Github dan Git Tools untuk Programmer sangat membantu sekali dan mudah dimengerti, harapannya dapat mempermudah segala project ataupun tugas yang diberikan. 

Penentuan Bilangan terbesar dari 3 Bilangan yang diinputkan kita mengetahui untuk mendapatkan hasilnya terdapat dua cara yang memudahkan kita, yaitu dengan code program Python memasukan input bilangan bulat atau pun decimal mampu mebantu kita mendapatkan jawaban saat di running, lalu cara lainnya adalah dengan Flowchart ini lebih kearah proses atau alur kita mendapatkan sebuah hasil dari Bilangan terbesar.