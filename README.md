# Tugas-Organisasi-dan-Arsitektur-Komputer

# 1. Jelaskan struktur antar hubungan BUS dan beri contohnya!

  Struktur antar Hubungan bisa disebut sebagai sistem BUS, jadi BUS adalah sebuah subsistem yang mentransfer data atau listrik antar komponen komputer di dalam sebuah komputer atau antar komputer.Pada sistem komputer, bus ini termasuk perangkat internal, kecepatan pengiriman informasi melalui bus ini dilakukan dengan kecepatan tinggi.
Contoh :

- PCI ( Pheripheral Component Interconnect )

   bus yang didesain untuk menangani beberapa perangkat keras. PCI juga adalah suatu bandwidth tinggi yang populer, prosesor independent bus itu dapat berfungsi sebagai bus mezzenine atau bus periferal. Standar bus PCI ini dikembangkan oleh konsorsium PCI Special Interest Group yang dibentuk oleh Intel Corporation dan beberapa perusahaan lainnya, pada tahun 1992. Tujuan dibentuknya bus ini adalah untuk menggantikan Bus ISA/EISA yang sebelumnya digunakan dalam komputer IBM PC atau kompatibelnya.

- USB ( Universal Serial Bus )

   USB merupakan suatu teknologi yang memungkinkan kita untuk menghubungkan alat eksternal (peripheral) seperti scanner, printer, mouse, papan ketik (keyboard), alat penyimpan data (zip drive), flash disk, kamera digital atau perangkat lainnya ke komputer kita. USB sangat mendukung transfer data sebesar 12 Mbps ( juta bit per detik). Komputer (PC) saat ini, umumnya sudah memiliki port USB. Biasanya disediakan minimal 2 port. Jika dibandingkan dengan paralel port dan serial port, penggunaan port USB lebih mudah dalam penggunaannya.

- BUS PCI

   Bus yang tidak tergantung prosesor dan berfungsi sebagai bus mezzanine atau bus peripheral. Standar PCI adalah 64 saluran data pada kecepatan 33MHz, laju transfer data 263 MB per detik atau 2,112 Gbps. Keunggulan PCI tidak hanya pada kecepatannya saja tetapi murah dengan keping yang sedikit.

- BUS ISA ( Industry Standart Architecture )

   Industri computer personal lainnya merespon perkembangan ini dengan mengadopsi standarnya sendiri, bus ISA, yang pada dasarnya adalah bus PC/AT yang beroperasi pada 8,33 MHz. Keuntungannya adalah bahwa pendekatan ini tetap mempertahankan kompatibilitas dengan mesin-mesin dan kartu-kartu yang ada.

# 2 Bila terlalu banyak modul atau perangkat dihubungkan pada bus maka akan terjadi penurunan kinerja, sebutkan penyebabnya?

Bila terlalu banyak modul atau perangkat dihubungkan pada bus maka akan terjadi penurunan
kinerja, yang disebabkan oleh :
  1. Semakin besar delay propagasi untuk mengkoordinasikan penggunaan bus.
  2. Antrian penggunaan bus semakin panjang.
  3. Dimungkinkan habisnya kapasitas transfer bus sehingga memperlambat data.
Antisipasi dan solusi persoalan di atas adalah penggunaan bus jamak yang hierarkis. Modulmodul diklasifikasikan berdasarkan kebutuhan terhadap lebar dan kecepatan bus. Bus biasanya
terdiri atas bus lokal, bus sistem, dan bus ekspansi.
 Habisnya kapasitas transfer Bus sehingga memperlambat data, jadi setiap bus mempunyai lebar bus masing-masing jika kapasitas transfer data disini melebihi maka transfer data akan lambat. 
  - Antrian penggunaan bus semakin panjang, Hal ini sama seperti memperlambat data jika banyak banyaknya penggunaan bus maka data juga lambat data mentransfer.
  - Semakin besar delay propagasi untuk mengkoordinasikan penggunaan bus.

# 3 Umumnya perangkat berprioritas paling rendah memiliki waktu tunggu rata-rata yang paling singkat. Dengan dasar ini biasanya CPU diberi perioritas tertinggi pada SBI. Sebutkan alasan perangkat berprioritas 16 memiliki waktu tunggu rata-rata paling rendah? Dibawah kondisi seperti apa keadaan diatas tidak berlaku?

 Bus data. Jalur yang berfungsi untuk menyalurkan data dari suatu bagian ke bagian lainnya. Berisi 8, 16, 32 jalur sinyal paralel atau lebih. Jalur-jalur data adalah dua arah (bidirectional). CPU dapat membaca dan mengirim data dari/ke memori atau port. Banyak perangkat pada sistem yang dicantolkan ke bus data tapi hanya satu perangkat pada satu saat yang dapat memakainya. Untuk mengatur ini, perangkat harus mempunyai tiga state  (tristate) agar dapat dipasang pada bus data.

# Berikut link sumber inforamasi di atas.
-Sumber nomor 1 (https://tugas-arsikom.blogspot.com/2020/05/tugas-5-struktur-antar-hubungan-bus.html)
-Sumber nomor 2 (http://file.upi.edu/Direktori/FPMIPA/PRODI._ILMU_KOMPUTER/HERBERT/KEL06-Arsitektur%26_Organisasi_Komputer_%281%29.pdf)
-Sumber nomor 3 (https://tecnomasi.blogspot.com/2015/12/jawaban-organisasi-arsitektur-komputer.html)
