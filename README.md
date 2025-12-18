# info4-project-deby-24105
Penggunaan super/jenis-jenis inheritance

# Deskripsi
Program ini dibuat untuk memenuhi pembelajaran pada mata kuliah
Pemrograman Berorientasi Objek (PBO) kelas info 4.
Program menggunakan bahasa pemrograman Python dengan menerapkan konsep Object Oriented Programming (OOP), khususnya pewarisan (inheritance) dan pewarisan ganda (multiple inheritance).
Konsep class, object, method, dan pemanggilan constructor menggunakan super() diterapkan agar program lebih terstruktur dan mudah dipahami.

# Fitur
- Menampilkan contoh pewarisan tunggal antara class Kendaraan dan Mobil
- Menampilkan contoh multiple inheritance pada class C yang mewarisi class A dan B
- Menampilkan data dan pemanggilan method dari class induk dan class turunan

# Penjelasan Program
- Class Kendaraan berfungsi sebagai class induk yang memiliki atribut merk, pembelian, dan pembayaran.
- Class Mobil merupakan class turunan dari Kendaraan yang mewarisi seluruh atribut induk dan menambahkan atribut baru yaitu warna.
- Fungsi super() digunakan untuk memanggil constructor dari class Kendaraan.
- Class A dan B masing-masing memiliki method sendiri.
- Class C mewarisi dua class sekaligus, yaitu A dan B, sehingga dapat mengakses seluruh method dari kedua class tersebut.

# Struktur Class
- Kendaraan : Class induk
- Mobil : Class turunan dari Kendaraan
- A dan B : Class induk untuk multiple inheritance
- C : Class turunan dari A dan B

# Cara Menjalankan
- Pastikan Python sudah terinstall di komputer
- Simpan kode program dalam satu file Python
- Jalankan program dengan perintah:
bast nama_file.py
