
## UTS Praktikum WEB: Pembuatan Formulir Input dengan PHP dan MySQL

---

### Deskripsi Project UTS:
Pada project UTS ini, Anda akan membuat sebuah formulir input sederhana dengan menggunakan HTML dan PHP untuk mengumpulkan data mahasiswa. Data yang dimasukkan melalui formulir akan disimpan ke dalam database MySQL. Tujuan dari UTS ini adalah memahami dasar-dasar pemrograman web, koneksi database, dan penggunaan formulir HTML.

### Langkah-langkah Pengerjaan:

1. **Persiapan Environment:**

    - Pastikan Anda telah menginstal server web lokal seperti XAMPP, WAMP, atau MAMP.
    - Pastikan server database MySQL sudah berjalan.

2. **Buat Database dan Tabel:**
    - Buatlah sebuah database MySQL dengan format `nim_namadepan` (tanpa spasi).
    - Buatlah tabel dengan `nama_tabel_bebas` sesuai dengan judul project yang telah ditentukan, minimal terdiri dari 5 buah kolom (*field*) dengan ketentuan atau contoh sebagai berikut:
        - Wajib memiliki kolom id / sesuai kasus Anda sebagai ***primary key*** dan juga ***auto increment***
        - Selain kolom id, silahkan tambahkan sesuai studi kasus Anda dan pastikan tipe data yang digunakan sesuai dengan kebutuhan.

3. **Buatlah Formulir PHP HTML:**
    - Buatlah sebuah halaman HTML dengan nama `index.php`.
    - Buatlah form untuk mengumpulkan data inputan minimal terdiri dari inputan dengan type input yang berbeda-beda minimal 4 tipe. Contoh `text|password|datetime|number|dan lain-lain`.
    - Tambahkan validasi pada form untuk menentukan suatu inputan wajib diisi atau opsional ataupun jumlah karakter minimum dan lain sebagainya sebelum formulir dapat dikirimkan.

4. **Menulis Kode Pemrosesan Data:**
    - Pastikan proses input ditulis menggunakan kode php.
    - Buat file PHP dengan nama `proses_input.php`.
    - Buat koneksi ke MySQL Server dan pastikan Anda mengganti pengaturan koneksi sesuai dengan pengaturan database Anda.
    - Simpan data yang ditampung pada formulir ke dalam database yang telah anda buat sebelumnnya.

5. **Tambahkan Styling CSS pada Formulir (Nilai tambah/opsional)**
	-   Jika Anda ingin mempercantik tampilan form , Anda  dapat menyesuaikan tampilan formulir tersebut dengan menambahkan CSS ke file `style.css`.
	-   Sesuaikan desain formulir agar menarik dan sesuai dengan tema dan tujuan formulir tersebut.

6. **Uji Coba:**
    - Pastikan server web lokal anda berjalan.
    - Buka browser dan akses `http://localhost/nama_folder/index.php` untuk melihat formulir input.
    - Isi formulir dengan data yang sesuai dan klik tombol "Simpan" atau "Save" (sesuai dengan yang dibuat).
    - Pastikan formulir berfungsi dengan baik tanpa ada error.
    - Pastikan data berhasil disimpan ke dalam database MySQL.
    - Setelah dilakukan uji coba dan berhasil silahkan lakukan export database anda menggunakan ***phpmyadmin***. **(format file *.sql)**

### Pengumpulan Project UTS :

-   Buat repository baru di ***GitHub/Gitlab*** dengan nama ***NIM_Nama_Kelas*** (contoh: 1906038_Novan_A ) untuk menyimpan *source code* praktikum ini. **(wajib menggunakan akun pribadi)**
-   Unggah semua file (PHP + HTML, CSS, Export Database, dan Screenshot form) yang Anda buat ke dalam repository tersebut.
-   Kirim link repository ***GitHub/Gitlab*** Anda sebagai pengumpulan tugas Project UTS.

### Catatan:

-   Project UTS ini memberikan kebebasan kepada mahasiswa untuk merancang formulir sesuai dengan preferensi pribadi atau studi kasus.
-   Untuk menjaga integritas pastikan bahwa setiap mahasiswa membuat form-input dengan `judul project` yang berbeda. **Contoh:** Form Pendaftaran Pasien Rumas Sakit, Form Pendaftaran Mahaisiswa, dll.
-   Penambahan desain dengan CSS bersifat opsional, namun kami menyarankan Anda untuk mengeksplorasi dan meningkatkan tampilan formulir sesuai dengan preferensi dan kreativitas Anda sehingga menjadi pertimbangan juga untuk penilaian.
- **Dilarang menggunakan project yang sudah ada sebelumnya atau pada saat praktikum**
- **Dilarang menggunakan project orang lain.**
- **Dilarang reusable project teman Anda.**
- **Jika ditemukan kecurangan atau plagiasi, nilai UTS otomatis mendapatkan score 40**
- **Dilarang membagikan soal ini kepada kelas yang belum melaksanakan UTS**

---

Jika ada instruksi yang tidak sepenuhnya dipahami, silakan ajukan pertanyaan melalui `Grup WhatsApp` yang disediakan atau bisa menghubungi Asisten dan Instruktur.
