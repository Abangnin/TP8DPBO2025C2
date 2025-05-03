# Bismillahirrahmanirrahim

## Janji
Saya Muhammad Naufal Arbanin dengan NIM 2310850 mengerjakan soal Tugas Praktikum 8 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Desain Program Sql
![Image](https://github.com/user-attachments/assets/a641fab3-65f1-49c1-addd-fdc53b18712f)

## Penjelasan Alur

### A. Alur Sistem CRUD Mahasiswa
#### 1. Tambah Mahasiswa (add)

- User membuka halaman tambah mahasiswa.

- User mengisi data: Nama, NIM, Jurusan, dan Phone.

- Saat klik simpan, data mahasiswa disimpan ke tabel students.

- Setelah berhasil, aplikasi redirect ke halaman daftar mahasiswa.

#### 2. Tampilkan Mahasiswa

- Pada halaman student_index, aplikasi mengambil data mahasiswa dari tabel students.

- Data ditampilkan dalam bentuk tabel, lengkap dengan opsi Edit dan Hapus.

#### 3. Edit Mahasiswa

- User memilih tombol Edit di tabel.

- Aplikasi membuka halaman edit, dengan form yang sudah terisi data mahasiswa yang dipilih.

- User bisa mengubah data, lalu klik update.

- Data yang diubah akan diperbarui di tabel students berdasarkan id mahasiswa.

#### 4. Hapus Mahasiswa

- User menekan tombol Hapus.

- Akan muncul konfirmasi. Jika setuju, data mahasiswa dihapus dari tabel students.

### B. Alur Sistem CRUD Genre Musik
#### 1. Tambah Genre Musik

- User membuka halaman tambah genre.

- User mengisi nama genre musik.

- Data genre disimpan ke tabel genres.

#### 2. Tampilkan Genre

- Pada halaman daftar genre, aplikasi ambil data dari tabel genres.

- Data ditampilkan dalam tabel dengan opsi Edit dan Hapus.

#### 3. Edit Genre

- User klik Edit, halaman form terbuka dengan data lama.

- User edit, lalu simpan.

- Data di-update di tabel genres.

#### 4. Hapus Genre

- User klik Hapus, muncul konfirmasi.

- Jika setuju, data genre dihapus dari tabel genres.

### C. Alur Sistem CRUD Musik
#### 1. Tambah Musik

- User buka halaman tambah musik.

- Isi data: judul musik dan pilih genre dari dropdown (data dari tabel genres).

- Data disimpan ke tabel musics dengan genre_id sebagai foreign key.

#### 2. Tampilkan Musik

- Halaman daftar musik ambil data dari tabel musics JOIN genres.

- Data ditampilkan dalam tabel, opsi Edit dan Hapus.

#### 3. Edit Musik

- User klik Edit, halaman form terbuka dengan data musik.

- Data diubah, simpan, update ke tabel musics.

#### 4. Hapus Musik

- User klik Hapus, konfirmasi muncul.

- Data musik dihapus dari tabel musics.

### D. Alur Sistem CRUD Kesukaan Musik
#### 1. Tambah Kesukaan Musik

- User buka halaman tambah kesukaan musik.

- Pilih Mahasiswa (dari tabel students) dan Musik (dari tabel musics) via dropdown.

- Data disimpan ke tabel kesukaan_musik dengan student_id dan music_id sebagai foreign key.

#### 2. Tampilkan Kesukaan Musik

- Halaman daftar kesukaan ambil data JOIN tabel kesukaan_musik, students, dan musics.

- Tampilkan tabel nama mahasiswa dan judul musik kesukaannya.

#### 3. Edit Kesukaan Musik

- User klik Edit, halaman form terbuka.

- Data diubah (pilih ulang mahasiswa atau musik), simpan.

- Data di-update di tabel kesukaan_musik.

#### 4. Hapus Kesukaan Musik

- User klik Hapus, muncul konfirmasi.

- Data dihapus dari tabel kesukaan_musik.

## Dokumentasi Video
https://github.com/user-attachments/assets/ff5671e7-5831-4abc-ba5e-b07cf36a9efe
