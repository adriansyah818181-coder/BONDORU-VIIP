BONDORU VIP — DEMO WEBSITE
==========================

CARA MENJALANKAN
1. Extract file ZIP ini.
2. Buka folder BONDORU_VIP di VS Code.
3. Buka file index.html.
4. Klik kanan > Open with Live Server (jika ekstensi Live Server tersedia).
   Alternatif: buka index.html langsung lewat browser.

AKUN DEMO ADMIN
Username: admin
Password: admin123

FITUR YANG SUDAH ADA (PROTOTIPE FRONTEND)
- Homepage BONDORU VIP
- Registrasi otomatis dan login demo
- Dashboard member
- Saldo game dan loyalty points (data demo)
- Halaman pemesanan jumlah game dan role
- Riwayat transaksi demo
- WDP info
- Admin: atur harga, buka/tutup order, lihat member dan pesanan
- Penyimpanan demo menggunakan localStorage browser

PENTING — BELUM SIAP PRODUKSI
Ini adalah prototype frontend untuk melihat alur dan desain website.
Belum ada backend/database online, autentikasi aman, payment gateway QRIS,
webhook pembayaran, pengiriman notifikasi, atau spin WDP sungguhan.
Tombol/status pembayaran dan penyelesaian order pada versi ini hanya simulasi.
Jangan gunakan password asli atau data pelanggan sungguhan.

ATURAN BISNIS YANG SUDAH DITERAPKAN DI TAMPILAN
- Role: Mid, EXP, Jungle, Roam, Gold Lane.
- Pembelian bisa lebih dari satu game.
- Persetujuan masa berlaku satu bulan dan tidak ada refund ditampilkan.
- Loyalty: Rp1.000 = 1 poin; level Bronze sampai Diamond.
- Order dapat dibuka/tutup dari admin demo.

CATATAN
Data disimpan di browser perangkat yang sama. Jika cache/site data dihapus,
data demo bisa hilang. Untuk versi online perlu backend (misalnya Node.js),
database (MySQL/PostgreSQL), autentikasi, dan payment gateway resmi.
