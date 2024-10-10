# Mesin Kasir Sederhana
# Tugas Asistensi P1

## Deskripsi Program
Mesin Kasir Sederhana merupakan Tugas Asisten Dasar Pemrograman untuk Praktikum P1 Pengenalan Bahasa C. Dalam program Mesin Kasir Sederhana berisi dapat menerima input berupa nama barang, harga, dan jumlah barang, kemudian menghitung total harga dan menampilkan struk belanja. setelahnya program ini juga dapat menambahkan diskon dan menampilkan harga setelah diskon sesuai dengan keinginan user. Program ini juga menyesuaikan kriteria yang harus ada di dalam Pemrogramannya.

## Fitur Utama dalam Program 
1. Memberikan tata cara pengisian
2. Menerima input nama, harga, dan jumlah barang untuk 3 item.
3. Menghitung dan menampilkan total harga untuk semua barang.
4. Menerima input diskon dan menampilkan harga sebelum dan setelah diskon.

## Struktur Program
- **struct Item**: Struct ini digunakan untuk menyimpan informasi tentang barang, termasuk nama, harga, dan jumlah.
  
- **print_receipt(struct Item items[], int itemCount, float discount)**: Fungsi ini bertugas untuk mencetak struk belanja. Fungsi ini menerima array barang (items), jumlah item (itemCount), dan diskon (discount). Struk menampilkan nama barang, harga per item, jumlah, total harga, diskon, dan total harga setelah diskon.

- **main()**: Fungsi utama program yang menerima input dari pengguna, seperti nama barang, harga, dan jumlah. Program ini juga menerima input diskon dan memanggil fungsi print_receipt untuk mencetak struk.

## OUTPUT
Output yang dikeluarkan oleh program berbentuk seperti struk dimana berisikan barang apa saja yang diinputkan user kemudian baru berisi harga sebelum diskon, total diskon, dan hasil harga setelah diskon dan harus dibayarkan. Salah keunggulan Program ini juga bisa menerima harga barang hingga nominal juta dan mengahsilkan output dalam nominal jutaan.
