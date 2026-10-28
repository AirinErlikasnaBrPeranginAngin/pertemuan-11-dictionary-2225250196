Tugas Algoritma dan Pemrograman — Pertemuan 11

Identitas Mahasiswa

- Nama: Airin Erlikasna Br Perangin Angin
- NIM: 2225250196
- Kelas: B

Tujuan

Mempelajari penggunaan dictionary dalam Python untuk menyimpan, mencari, menambah, mengubah, dan menampilkan data mahasiswa.

Struktur Data

Program menggunakan dictionary dengan NIM sebagai key. Setiap NIM memiliki dictionary bersarang yang berisi nama, kelas, dan nilai mahasiswa.

Fitur Program

1. Mencari mahasiswa berdasarkan NIM.
2. Menampilkan pesan jika NIM tidak ditemukan.
3. Menambahkan mahasiswa baru.
4. Mengubah nilai mahasiswa.
5. Menampilkan seluruh data mahasiswa.
6. Menghitung rata-rata nilai mahasiswa.

Cara Menjalankan

Jalankan perintah berikut melalui terminal VS Code:

python praktik/data_mahasiswa.py

Pengujian Program

Pengujian| Hasil yang Diharapkan| Status
Mencari NIM A003| Data Citra ditemukan| Berhasil
Mencari NIM A999| Data tidak ditemukan| Berhasil
Menambah NIM A006| Data Fajar ditambahkan| Berhasil
Mengubah nilai A002| Nilai Budi menjadi 82| Berhasil
Menampilkan seluruh data| Enam mahasiswa ditampilkan| Berhasil
Menghitung rata-rata| Rata-rata ditampilkan| Berhasil

Refleksi

Saya mempelajari bahwa dictionary menyimpan data dalam pasangan key dan value. NIM dapat digunakan sebagai key untuk mencari data mahasiswa. Saya juga belajar menggunakan "get()" untuk pencarian yang aman, "items()" untuk menampilkan pasangan key dan value, serta fungsi untuk menghitung rata-rata nilai.

Kuis Pertemuan 11

1. Apa perbedaan list dan dictionary?

List menggunakan indeks untuk mengakses data, sedangkan dictionary menggunakan key.

2. Apa fungsi key dalam dictionary?

Key berfungsi sebagai identitas untuk mengakses value yang tersimpan.

3. Apa yang terjadi jika "data["kelas"]" dipanggil ketika key ""kelas"" tidak ada?

Python akan menghasilkan error "KeyError".

4. Apa perbedaan "data["kelas"]" dan "data.get("kelas")"?

"data["kelas"]" menghasilkan "KeyError" jika key tidak ada, sedangkan "data.get("kelas")" menghasilkan "None" jika key tidak ditemukan.

5. Bagaimana cara memeriksa apakah suatu key ada dalam dictionary?

Menggunakan operator "in", misalnya "if "kelas" in data:".

6. Apa fungsi "items()" dalam dictionary?

"items()" digunakan untuk mengambil pasangan key dan value.

7. Bagaimana cara menambahkan pasangan key-value baru?

Menggunakan penugasan, misalnya "data["kelas"] = "A"".

8. Bagaimana cara mengubah value dari key yang sudah ada?

Menetapkan nilai baru pada key tersebut, misalnya "data["nilai"] = 90".

9. Mengapa NIM cocok digunakan sebagai key dalam data mahasiswa?

Karena NIM berfungsi sebagai identitas unik untuk membedakan mahasiswa.

10. Apa perintah Git untuk mengirim commit ke GitHub?

Menggunakan perintah "git push".

Tugas ini dibuat untuk memenuhi praktikum Algoritma dan Pemrograman Pertemuan 11.