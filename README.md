# Face-reconition-dengan-eigenface
Face Recognition merupakan teknologi biometrik yang digunakan untuk mengidentifikasi wajah seseorang demi berbagai kepentingan, khususnya keamanan. Program ini melibatkan kumpulan citra wajah yang sudah disimpan pada database lalu program dapat mempelajari bentuk wajah  berdasarkan kumpulan citra wajah tersebut dan mencocokkannya dengan citra yang akan diidentifikasi. 
Pada projek ini digunakan eigenface yang merupakan metode pengenalan wajah yang menggunakan konsep nilai eigen dan vektor eigen. Metode ini bekerja dengan mengubah kumpulan gambar wajah menjadi sekumpulan vektor, lalu mencari ciri utama wajah menggunakan PCA (Principal Component Analysis). 

Kelompok 10 
Nama anggota:
1. PHOEBE THEODORE BEATRICE	L0125060
2. RESPANANDA AYUNING TYAS	L0125064
L3. UCYANA DORA NOVIYANTI	L0125121

#Cara menjalankan dan menggunakan aplikasi:
1.	Download library yang dibutuhkan oleh program dengan menggunakan bash berikut pada command prompt computer. Pastikan library yang sudah di download berada pada path. bash: pip install numpy opencv-python pillow
2.	Jalankan kode dari file main.py.
3.	Setelah aplikasi terbuka dari jendela baru, masukkan file dataset yang sudah disimpan pada folder dengan mengklik tombol warna ungu yang bertuliskan ”Pilih Folder Dataset” .
4.	Masukkan folder dataset, baik yang langsung berisi kumpulan foto atau folder-folder lainnya, yang diinginkan. Setelah memilih folder, klik ”Select folder”.
5.	Kemudian masukkan foto yang ingin dites dengan mengklik tombol kuning yang bertuliskan ”Pilih Gambar”. Setelah memilih foto, klik ”Open”.
6.	Setelah file dataset dan foto terkumpul, klik tombol warna pink yang bertuliskan ”Run Recognition!”.
7.	Aplikasi akan menampilkan hasilnya, baik sama persis seperti pada foto, foto orang yang berbeda, atau tidak menampilkan foto karena tidak ada pada dataset.
