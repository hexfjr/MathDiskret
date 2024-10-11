# Algoritma

## Definisi Algoritma
Algoritma adalah Runtutan pengambilan putusan secara logis 
untuk pemecahan masalah.

Algoritma atau dengan kata lain Logic, merupakan komponen dasar dalam pembuatan 
sebuah Aplikasi Program. Ciri - ciri algoritma yang baik meliputi: 
Input, Output, Definite, Efective 
dan Terminate. 
Maksudnya adalah sebuah Algoritma harus memiliki Masukan dan Hasil, Juga memiliki  kejelasan  apa  yang  dilakukan,  serta  langkah  penyelesaian  yang efektif  dan  langkah tersebut  dapat  berhenti  atau  dapat  diberhentikan  secara  jelas. 


### Algoritma Sequential Search
Sequential  Search  adalah  teknik  pencarian  data  dimana  data  dicari  secara  urut dari depan  ke belakang  atau  dari  awal  sampai  akhir.  Berdasarkan  key  yang  dicari  Kelebihan  dari  proses  pencarian secara  sequential ini jika data  yang dicari terletak didepan , maka data  akan ditemukan dengan cepat. Tetapi  dibalik  kelebihannya  ini,  teknikini  juga  memiliki  kekurangan  jika  data  yang  dicari  terletak dibelakang  atau  paling  akhir,  maka  akan  membutuhkan  waktu  yang  lama  dalam  proses  pencariannya dan juga beban komputer akan semakin bertambah jika jumlah data dalam array sangat banyak. 


### Algoritma Binary Search

Binary  Search  adalah algoritma  pencarian  yanglebih efisien  daripada  Sequential  Search.  Hal  tersebut  dikarenakan algoritma  ini  tidak  perlu  menjelajahi  setiap  elemen  dari  tabel. Kerugiannya  adalah  algoritma  ini  hanya  bisa  digunakan  pada tabel  yang  elemennya  sudah  terurut  baik  menaik  maupun menurun. Pada  intinya,  algoritma  ini  menggunakan  prinsip divide   and   conquer, dimana   sebuah   masalah   atau   tujuan diselesaikan  dengan  cara  mempartisi  masalahmenjadi  bagian yang lebih kecil. Algoritma ini membagi sebuah tabel menjadi duadan  memproses  satu  bagian  dari  tabel  itu  saja.  Algoritma ini bekerja  dengan caramemilih record dengan indeks tengah dari tabel dan membandingkannya denganrecord yang hendak dicari.  Jika  record  tersebut  lebih  rendah  atau  lebih  tinggi,maka   tabel   tersebut   dibagi   dua   dan   bagian   tabel   yang bersesuaian akan diproseskembali.Prinsip pencarian biner dapat dijelaskan sebagai berikut :Misalkan indeks kiri adalah i dan indeks kanan adalah j. Pada mulanya, melakukan inisialisasi i dengan 1 dan j dengan n.

1. Bagi dua elemen larik pada elemen tengah. Elemen tengah adalah elemendengan indeks k = (i + j) div. <br>
2. ( Elemen tengah L[K], membagi larik menjadi dua bagian yaitu bagian kiri L[i..j] dan bagian kanan L[k+1..j]) 2. Periksa apakah L[K] = x, jika L[K] = x maka pencarian selesai sebab x sudah ditemukan. Tetapi jika L[K] ≠ x, harus ditentukan apakah pencarian akan dilakukan di larik bagian kiri atau dilarik bagian kanan. Jika L[K] < x, maka pencarian dilakukan lagi pada larik bagian kiri.

## Pseudocode adalah...

Pseudocodeadalah Pseudocodeadalah  kode  atau tanda   yang   menyerupai   (pseudo)   atau   penjelasan   cara menyelesaikan suatu masalah. Pseudocodesering digunakan untuk   menuliskan   algoritma   dari   suatu   permasalahan. Pseudocodeberisikan langkah-langkah untuk menyelesaikan suatu  permasalahan  dan  hampir  sama  dengan  algoritma, hanya   saja   bentuknya   sedikit   berbeda   dari   algoritma. Pseudocodemenggunakan  bahasa  yang  hampir  menyerupai bahasa   pemrograman.   Selain   itu   biasanya Pseudocodemenggunakan bahasa yang mudah dipahami secara universal dan juga lebih ringkas dari pada algoritma.

## Big O algoritma

## Hitung Big O dari Algoritma Sequantial Search

* ** Waktu kompleksitas **

* ** Ruang Kompleksitas **


### Refrensi: 
1. (Definisi Algoritma) Joseph Teguh Santoso. (2021). STRUKTUR DATA dan ALGORITMA (Bagian 1). Penerbit Yayasan Prima Agus Teknik, 7(1), 1-333. Retrieved from https://penerbit.stekom.ac.id/index.php/yayasanpat/article/view/288
2. (Algoritma Sequential Search) Mochamad Aminnur, Radja Susun Pakpahan, Dhamar Galih Alfarizi, Diski Apriana, Sutisna Mustika Rahmat, Ahmad Fauzi, & Perani Rosyani. (2023). IMPLEMENTASI METODE SEQUENTIAL SEARCH UNTUK PENGELOLAAN DATA BARANG PADA SISTEM APLIKASI SIKILAT CARGO. LOGIC : Jurnal Ilmu Komputer Dan Pendidikan, 1(2), 283–287. Retrieved from https://www.journal.mediapublikasi.id/index.php/logic/article/view/1629
3. (Algoritma Binary Search) Achmad Nur Santoso, Adi Indera Dwi Anggara, Alfin Firman Syah, Luthfianti Wahyu Noerlillah, & Wahyu Surya Alamsyah. (2018). Sistem Kontrol Perpustakaan Menggunakan Metode Binary Searching. SinarFe7, 1(1), 365–368. Retrieved from https://journal.fortei7.org/index.php/sinarFe7/article/view/203
4. Priambodo, Y. A., & Prasetyo, S. Y. J. (2018). Pemetaan Penyebaran Guru di Provinsi Banten dengan Menggunakan Metode Spatial Clustering K-Means (Studi kasus : Wilayah Provinsi Banten). Indonesian Journal of Computing and Modeling, 1(1), 18–27. Retrieved from https://ejournal.uksw.edu/icm/article/view/1491
5. (Big O algoritma)
6. (Hitung Big O dari Algoritma Sequantial Search)