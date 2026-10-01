DompetKu - Aplikasi Keuangan Pribadi Fullstack (Tanpa Backend)

DompetKu adalah aplikasi web pencatatan keuangan pribadi yang modern, responsif, dan terintegrasi langsung dengan Google Spreadsheet sebagai database awan (cloud database) tanpa memerlukan server backend terpisah.

🌟 Fitur Unggulan

Dashboard Interaktif:

Menampilkan 3 kartu ringkasan utama: Saldo Saat Ini, Pemasukan Bulan Ini, dan Pengeluaran Bulan Ini.

Grafik garis interaktif (Chart.js) untuk memantau perbandingan pemasukan dan pengeluaran 7 hari terakhir.

Input Transaksi Mudah:

Tombol melayang (+) di sudut kanan bawah untuk menambah transaksi baru.

Form popup lengkap dengan pilihan Tipe (Masuk/Keluar), Nominal Rupiah, Kategori (Makan, Transport, Gaji, Jajan, Tagihan, Lainnya), Tanggal, dan Catatan.

Rekap & Laporan Fleksibel:

Tab Rekap dengan filter Harian, Mingguan, dan Bulanan.

Dilengkapi diagram batang rekap bulanan serta filter berdasarkan Kategori.

Database Google Spreadsheet:

Menggunakan Google Apps Script (doGet dan doPost) sebagai API endpoint.

Data tersimpan aman di spreadsheet pribadi Anda.

Penyimpanan Lokal & Konfigurasi URL Fleksibel:

URL Google Apps Script disimpan di localStorage browser. Jika belum diatur, aplikasi otomatis berjalan dengan mode penyimpanan lokal (demo).

🚀 Cara Instalasi & Deploy ke GitHub Pages

Langkah 1: Siapkan Google Spreadsheet & Apps Script

Buat Google Spreadsheet baru di Google Drive Anda, beri nama "Database DompetKu".

Buka menu Extensions > Apps Script.

Masukkan kode dari file APPS_SCRIPT_CODE.txt ke dalam editor Apps Script.

Klik Deploy > New Deployment, pilih tipe Web App.

Execute as: Me

Who has access: Anyone

Salin Web App URL yang dihasilkan.

Langkah 2: Upload File ke GitHub

Buat repository baru di GitHub (misal: dompetku).

Unggah file index.html ke dalam repository utama (root). Anda juga boleh menyertakan file README.md.

Masuk ke tab Settings repository GitHub Anda.

Pilih menu Pages di bagian sidebar kiri.

Pada bagian Build and deployment, pilih Source: Deploy from a branch dan Branch: main / root, lalu klik Save.

Dalam beberapa menit, GitHub akan memberikan URL live situs web Anda.

Langkah 3: Hubungkan DompetKu ke Google Sheet Anda

Buka tautan GitHub Pages DompetKu Anda.

Klik tombol Konfigurasi API di pojok kanan atas.

Tempelkan URL Web App Google Apps Script Anda, lalu klik Simpan URL.

Aplikasi siap digunakan sepenuhnya!

© 2026 DompetKu Keuangan Pribadi. Dibuat dengan Tailwind CSS & Chart.js.
