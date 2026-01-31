## Deskripsi Proyek
Permainan Tebak Angka adalah aplikasi berbasis web sederhana yang menantang pemain untuk mencari angka rahasia antara 1 hingga 100. Proyek ini dirancang untuk mendemonstrasikan logika dasar pemrograman JavaScript, manipulasi DOM, dan desain responsif menggunakan CSS.

## Fitur Utama
* Logika Tebakan: Memberikan umpan balik instan apakah angka terlalu tinggi atau terlalu rendah.
* Sistem Poin: Skor maksimal 1000 yang akan berkurang seiring banyaknya kesalahan.
* Fitur Petunjuk: Tersedia 3 jenis bantuan yang mencakup informasi ganjil/genap, digit depan, dan rentang angka.
* Riwayat Tebakan: Mencatat setiap angka yang telah dimasukkan untuk menghindari pengulangan.
* Desain Responsif: Tampilan yang menyesuaikan secara otomatis untuk perangkat desktop maupun ponsel.

## Teknologi
* HTML5
* CSS3
* JavaScript (ES6)

## Cara Menjalankan
1. Unduh atau salin kode sumber proyek.
2. Simpan sebagai file dengan ekstensi .html (contoh: index.html).
3. Buka file tersebut menggunakan browser web modern seperti Chrome, Firefox, atau Edge.

## Aturan Permainan
1. Pemain memasukkan angka pada kolom input.
2. Pemain dapat melihat riwayat tebakan untuk membantu strategi selanjutnya.
3. Terdapat batas maksimal 3 kali penggunaan petunjuk.
4. Permainan berakhir jika angka berhasil ditemukan atau skor mencapai angka 0.

## Struktur Kode
* CSS: Mengatur tata letak menggunakan Flexbox dan memberikan tema gelap (dark mode).
* JavaScript: Mengelola status permainan melalui fungsi initGame(), processGuess(), dan giveHint().
