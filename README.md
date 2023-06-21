# LP12DPBO2023C2

# Janji

Saya Talitha Syahla NIM 2101330 mengerjakan Soal Latihan 12 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Alasan

Alasan saya menggunakan Model-View-ViewModel (MVVM) pada Latihan Praktikum 12 ini adalah karena pada MVVM ini memilki relasi One To Manny, jadi memberikan kemudahan dalam melakukan pengujian unit program. Proses MVVM ini juga menurut saya lebih efisien. MVVM ini akan mengakses view saat pengguna masuk, disini file synchronization saya jadikan sebagai View karena sudah mencakup dari file game.

# Perbedaan Struktur LP dan TMD

Untuk framework yang digunakan di TMD masih sama dengan LP, yaitu Model-View-ViewModel (MVVM). Namun ada tambahan file di package `Model` yaitu file `DB` untuk database dan file `TableScore` untuk tampilan tabel score. Adapun tambahan file di package `ViewModel` yaitu file `Musik` untuk menambahkan backsound saat game dijalankan oleh user.

Pada struktur LP, file `Display` yang berfungsi untuk menampilkan tampilan ini terdapat di package `Model`. Namun pada struktur Tugas Masa Depan (TMD) yang saya gunakan, adapun file `GameWindow` yang digunakan untuk menampilkan tampilan sama seperti file `Display` ada di package `View`.

Selain itu, pada LP terdapat file `Handler` yang memiliki fungsi untuk menghandle `GameObject` ini berada di package `Model`. Namun pada struktur Tugas Masa Depan (TMD) yang saya gunakan, terdapat file `ObstacleHandler` di package `ViewModel` yang memiliki fungsi untuk menghandle file `Obstacle` yang ada di package `Model`.
