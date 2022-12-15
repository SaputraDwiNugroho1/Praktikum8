# Tugas Praktikum 8
Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan :
- Method tambah() untuk menambah data
- Method tampilkan() untuk menampilkan data
- Method hapus(nama) untuk menghapus data berdasarkan nama
- Method ubah(nama) untuk mengubah data berdasarkan nama
- Buat diagram class, flowchart dan penjelasan programnya pada README.md.
- Commit dan Push repository ke Github.

TULIS SOURCE CODE SEPERTI GAMBAR DI BAWAH INI :
![gambar 1](ss/1.png)
![gambar 2](ss/2.png)
![gambar 3](ss/3.png)

HASIL RUN :
- Tambah Data
![gambar 4](ss/4.png)

- Lihat Data
![gambar 5](ss/5.png)

- Keluar
![gambar 6](ss/6.png)

## Penjelasan
- Pertama kita mendeklarasikan sebuah class mahasiswa yang didalamnya terdapat atribut NIM, Nama, nilai tugas, nilai UTS dan nilai UAS. JANGAN LUPA, untuk mendeklarasikan sebuah class didalam OOP kita harus menggunakan def_init_ dan juga self.
- Seperti biasa, deklarasikan satu dictionary kosong sebagai tempat menyimpan data-data yang sudah kita input. Ada 5 list kosong yang nantinya berisi NIM, Nama, nilai tugas, nilai UTS, dan nilai UAS.
- Kita akan buat beberapa method untuk menambahkan, menampilkan, mengubah, dan menghapus data mahasiswa. Pertama membuat method tambah(), method ini berfungsi untuk menambahkan data. Dalam method ini kita menggunakan append() agar data yang terakhir ditambahkan ada di urutan list paling akhir.
- Fungsi membuat method lihat() yaitu untuk menampilkan seluruh data yang sudah kita tambahkan tadi. Jika tidak ada data sama sekali, maka akan muncul tulisan TIDAK ADA DATA.
- Fungsi membuat method ubah() yaitu untuk mengubah data. jika method ini diinput, maka data Nama, NIM, nilai tugas, nilai UTS, nilai UAS index nomor - (no) akan diubah sesuai dengan inputan dari user. Index ke - (no) akan dicari secara otomatis sesuai dengan nama yang ingin diubah oleh user.
- Terakhir kita membuat method hapus(), yang berfungsi untuk menghapus data berdasarkan nama. Kita bisa menggunakan del untuk menghapus datanya. Seperti sebelumnya, nomor index list yang akan dihapus disesuaikan dengan inputan dari user. Yaitu index nomor ke - (no).

## Diagram Class

![gambar 7](ss/7.png)


## Flowchart Praktikum 8

![gambar 8](ss/8.png)
