# Koreksi Lembar Jawab (LJK) — SMPN 1 Sukamantri

Aplikasi web progresif (PWA) berbahasa Indonesia untuk mengoreksi lembar jawab pilihan ganda (40 atau 50 soal, A–D) secara otomatis langsung dari kamera HP tanpa internet dan tanpa server.

**Pembuat:** Dian Fitriana, S.Kom · SMPN 1 SUKAMANTRI

---

## 1. Cara Unggah ke GitHub Pages (Gratis)
1. Masuk ke akun [GitHub](https://github.com) dan buat repositori baru bernama `koreksi-ljk` (pilih **Public**).
2. Ekstrak berkas `koreksi-ljk-github.zip`, lalu unggah seluruh isinya (`index.html`, `sw.js`, `manifest.webmanifest`, folder `icons/`, dan folder `lembar/`) ke repositori tersebut.
3. Buka menu **Settings → Pages** pada repositori Anda.
4. Pada bagian **Build and deployment → Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**.
5. Tunggu ±1 menit hingga tautan `https://<username>.github.io/koreksi-ljk/` aktif.

## 2. Cara Memasang di HP (Android & iPhone)
- **Android (Chrome):** Buka tautan aplikasi → ketuk ikon titik tiga di pojok kanan atas → pilih **Tambahkan ke layar utama (Install app)**.
- **iPhone (Safari):** Buka tautan aplikasi di Safari → ketuk tombol **Bagikan (Share)** di bawah → pilih **Tambah ke Layar Utama (Add to Home Screen)**.

## 3. Cara Mencetak Lembar Jawab
1. Unduh berkas cetak dari menu **Pengaturan → Lembar Jawab** (`lembar/ljk-a4.pdf` untuk kertas A4 atau `lembar/ljk-f4.pdf` untuk kertas F4/Folio).
2. Cetak dengan pengaturan ukuran **100% / Actual Size** (jangan *Fit to Page* agar proporsi kotak sudut tetap akurat).
3. Satu kertas menghasilkan **3 lembar jawab** (dapat dipotong menjadi 3 bagian atau dipindai 1 lembar utuh sekaligus).

## 4. Cara Pakai dalam Tiga Langkah
1. **Pengaturan:** Isi jenis ujian, mata pelajaran, kelas, jumlah soal (40/50), dan kunci jawaban.
2. **Pindai:** Ketuk tombol kamera, arahkan ke lembar jawab hingga 4 kotak hitam di sudut terdeteksi hijau, lalu tunggu pemotretan otomatis (atau tekan tombol potret putih). Periksa nomor yang ditandai **Cek Ulang** jika ada arsiran ragu-ragu.
3. **Hasil:** Lihat peringkat kelas, analisis tingkat kesukaran butir soal, dan ekspor nilai ke **CSV** (Excel).

> **Saran Pengujian:** Lakukan uji coba memindai **5–10 lembar asli** yang diisi pensil 2B/pulpen sebelum hari ujian untuk memastikan pencahayaan kelas dan hasil cetakan printer terbaca optimal.
