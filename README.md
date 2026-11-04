# DashboardOwner Demo

Salinan demo dari `leovbr/dashboardowner` yang berjalan sepenuhnya menggunakan localStorage.

## Batasan demo
- Semua akun, katalog, transaksi, stok, laporan, pengeluaran, profil, dan data tim disimpan di browser/perangkat yang sama.
- Tidak ada koneksi Supabase, database cloud, Edge Function, atau sinkronisasi lintas perangkat.
- Data bisa hilang jika storage browser dibersihkan. Kapasitas localStorage terbatas; file besar tidak cocok disimpan di sini.
- Login dan password hanya simulasi UI, bukan autentikasi aman. Jangan gunakan password asli atau data usaha sensitif.
- Untuk menguji alur staff, buat akun dari menu **Tim & Akun** pada browser yang sama.

## GitHub Pages
Aktifkan melalui **Settings → Pages → Deploy from a branch → main → /(root) → Save**.
URL: https://leovbr.github.io/dashboardowner-demo/
