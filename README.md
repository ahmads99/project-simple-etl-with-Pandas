# Project Simple ETL with Pandas

## Deskripsi
Membangun ETL sederhana untuk mengelola dan mentransformasi data menggunakan library Pandas. Tujuan dari proyek ini adalah untuk melakukan berbagai transformasi data agar sesuai dengan format yang dibutuhkan dalam analisis lebih lanjut.

## Langkah-langkah yang Sudah Dikerjakan

### 1. **Impor Library Pandas**
   - Mengimpor library `pandas` untuk mempermudah manipulasi data.

### 2. **Memuat dan Memverifikasi Dataset**
   - Memuat dataset `dqthon-participants.csv`.
   - Memverifikasi dan mengeksplorasi data awal untuk memahami struktur dan konten yang ada.

### 3. **Transformasi Data**
   - **Bagian I - Kode Pos:**  
     Menambahkan kolom baru `postal_code` yang diekstrak dari kolom `address` dengan menggunakan teknik string manipulation.
   
   - **Bagian II - Kota:**  
     Menambahkan kolom baru `city` yang diambil dari bagian alamat di kolom `address`, memanfaatkan pemisahan string berdasarkan tanda koma.

   - **Bagian III - GitHub Profile:**  
     Membuat kolom `github_profile` dengan menggabungkan nama depan dan belakang dalam format URL GitHub seperti `https://github.com/<nama_depan><nama_belakang>`.
   
   - **Bagian IV - Nomor Handphone:**  
     Melakukan pembersihan pada kolom nomor handphone, mengubah awalan kode negara Indonesia, serta menghapus karakter tidak perlu (tanda baca atau spasi).

   - **Bagian V - Nama Tim:**  
     Membuat kolom `team_name` yang merupakan gabungan dari singkatan nama depan, nama belakang, negara, dan institusi, yang dapat digunakan sebagai identitas tim peserta.

   - **Bagian VI - Email:**  
     Membuat kolom `email` dengan format `<nama_depan>.<nama_belakang>@<institusi>.com`.

## Hasil yang Dicapai
Melalui proyek ini, dataset yang awalnya berantakan dan tidak terstruktur berhasil ditransformasi menjadi format yang lebih rapi dan siap digunakan untuk analisis lebih lanjut.
