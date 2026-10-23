# TradeFlow Journal v2.2

Aplikasi jurnal trading personal berbasis HTML, CSS, dan JavaScript. Data disimpan secara lokal di browser melalui `localStorage`.

## Fitur
- Header ringkas: avatar, nama, tanggal, pengaturan, dan ekspor CSV.
- Modal pengaturan terpadu untuk nama/foto profil, modal awal IDR, dan kurs IDR/USD.
- Navigasi bawah: Home, Analitik, Jurnal Trading.
- Home: equity, return kumulatif, profit/loss, transaksi terbaru, dan catatan evaluasi harian.
- Jurnal: banyak posisi per tanggal, instrumen Forex/komoditas/indeks/crypto, BUY/SELL, lot, ROI, catatan, edit/hapus, ekspor CSV.
- Analitik: kurva equity dimulai dari modal awal, serta donut profit/loss proporsional dan metrik statistik.
- Tema dark navy, ikon Lucide, animasi ringan dan dukungan `prefers-reduced-motion`.

## Jalankan lokal
Buka `index.html` di browser modern. Chart.js dan Lucide dimuat melalui CDN, sehingga koneksi internet dibutuhkan untuk kedua pustaka tersebut.

## Publikasikan di GitHub Pages
1. Unggah `index.html` ke repository GitHub (di root repository).
2. Pilih **Settings → Pages**.
3. Pilih branch utama dan folder `/ (root)`, lalu simpan.
4. Buka URL Pages setelah proses deploy selesai.

## Catatan data
Data hanya tersimpan di browser/perangkat yang digunakan; tidak ada sinkronisasi akun atau server. Ekspor CSV secara berkala sebagai cadangan sebelum mengganti versi aplikasi. Foto profil disimpan sebagai data lokal di browser.
