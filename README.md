# PHILKANET — Wireframe Mikhmon

Prototipe statis responsif untuk 8 lokasi awal. Buka `docs/index.html` di browser. Tidak perlu instalasi dependensi atau build.

## Interaksi

Pencarian/filter lokasi, detail lokasi, perpindahan lokasi, tab ringkasan/voucher/pengguna/pengaturan, pembuatan voucher simulasi, dan penambahan lokasi sementara. Semua angka/status adalah contoh, bukan hasil koneksi. Muat ulang halaman mengembalikan data awal. Tidak ada autentikasi nyata atau penyimpanan kredensial.

## GitHub Pages

1. Source tersedia di repository `galihadi432/philka`, branch `main`.
2. Buka Settings → Pages → Build and deployment.
3. Pilih GitHub Actions sebagai Source. Workflow `.github/workflows/pages.yml` menerbitkan folder `docs`.
4. Tunggu deployment dan buka URL yang diberikan GitHub Pages.

Semua aset memakai path relatif; navigasi hash mendukung URL project seperti `https://USERNAME.github.io/REPOSITORY/` tanpa aturan rewrite. Source sudah diunggah. Aktivasi Pages tertahan: paket akun saat ini tidak mendukung Pages untuk repository privat ini. Pemilik dapat memilih repository publik atau paket yang mendukung Pages privat; jangan mengubah visibilitas tanpa keputusan pemilik.

GitHub Pages tidak menjalankan PHP. Aplikasi Mikhmon operasional memerlukan server backend terpisah untuk menjalankan PHP dan mengakses API router. Jangan unggah folder konfigurasi Mikhmon asli atau kredensial ke situs ini.

Dokumentasi: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

