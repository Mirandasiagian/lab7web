# PHP Framework (Codeigniter4)
| Praktikum 3 framework lanjutan (CRUD) |  Pemrograman Web 2  
|-------|---------
| NIM   | 312310008
| Nama  | MIRANDA OKTAVIA SIAGIAN
| Kelas | TI.23.C1
| Dosen |  Agung Nugroho, S.Kom., M.Kom.

## Praktikum 1

Lengkapi kode program untuk menu lainnya yang ada pada Controller Page, sehingga semua
link pada navigasi header dapat menampilkan tampilan dengan layout yang sama.

- Halaman About

![gambar](./image/gambar1.png)

- Artikel

![image](./image/gambar7.png)

- Kontak

![image](./image/gambar2.png)

## Praktikum 2

Selesaikan programnya sesuai Langkah-langkah yang ada.

- Admin Portal Berita

![image](./image/gambar13.png)

- Add Data

![image](./image/gambar16.png)

- Edit Data

![image](./image/gambar19.png)

## Praktikum 3

<b>Pertanyaan & Tugas</b>
- Apa manfaat utama dari penggunaan View Layout dalam pengembangan aplikasi?

<b>Manfaat Utama View Layout</b>

- Memisahkan logika dan tampilan aplikasi (separation of concerns)

- Memungkinkan penggunaan kembali kode tampilan (reusability)

- Mempermudah pemeliharaan dan pengembangan aplikasi

- Meningkatkan konsistensi tampilan antar halaman

<b>Perbedaan View Cell dan View Biasa</b>

- iew Cell adalah komponen yang dapat merender bagian tampilan tertentu secara independen dan dapat di-cache, sementara View biasa adalah template lengkap yang tidak memiliki fitur caching bawaan dan biasanya digunakan untuk halaman lengkap.

Going on

![image](./image/gambar3.png)

## Praktikum 4
-  Halaman Login dengan filter Auth pada Config/Routes.php, menyimpan database dengan UserSeeder.

![image](./image/gambar25.png)

- Setelah Login & Masuk ke halaman Admin Artikel.

![image](./image/gambar26.png)

## Praktikum 5
- Membuat Pagination

Pagination merupakan proses yang digunakan untuk membatasi tampilan yang panjang
dari data yang banyak pada sebuah website. Fungsi pagination adalah memecah tampilan
menjadi beberapa halaman tergantung banyaknya data yang akan ditampilkan pada
setiap halaman.

Untuk membuat pagination, buka Kembali App/Controller/Artikel, kemudian modifikasi kode
pada method public function admin_index seperti berikut.

![image](./image/hasil2.png)

Kemudian buka kembali file App/Views/artikel/admin_index.php dan tambahkan form
pencarian sebelum deklarasi tabel seperti berikut:

![image](./image/hasil3.png)

Dan pada link pager ubah seperti berikut.
App/Views/artikel/admin_index.php bagian paling bawah diatas footer

![image](./image/hasil4.png)

Hasilnya akan seperti ini:

![image](./image/admin.png)

### Going on
