# Kopi Ratuku Landing Page

Landing page statis untuk brand kopi bubuk **Kopi Ratuku**. Halaman ini menonjolkan hero slider interaktif, katalog produk bubuk kopi, galeri foto lokal, testimoni pelanggan, hingga form promo diskon.

## Fitur Utama
- **Hero slider otomatis** dengan 4 foto lokal (`assets/img/`) lengkap kartu highlight yang responsif.
- **Navigasi mobile** dengan hamburger menu yang membuka/menutup mulus ketika tautan dipilih.
- **Seksyen produk** menampilkan varian kopi bubuk Signature, Arabica Gayo, dan Rempah Nusantara.
- **Galeri Curated Stories** berbentuk grid foto untuk menonjolkan storytelling visual.
- **CTA Promo** dengan form email untuk kampanye diskon 15%.
- Desain sepenuhnya responsif memakai CSS custom tanpa framework besar.

## Struktur Proyek
```
.
├── assets/
│   └── img/         # Seluruh foto slider, produk, dan galeri
├── index.html       # Markup utama landing page
├── style.css        # Styling utama + aturan responsif
└── logo.jpg         # Logo yang dipakai di header
```

## Cara Menjalankan
1. **Kloning / salin** folder `ratuku` ke environment lokal.
2. Pastikan seluruh aset gambar berada di `assets/img/`.
3. Buka `index.html` langsung di browser, atau gunakan static server (contoh `npx serve` atau `php -S localhost:8000`) agar path relatif tetap aman.

## Kustomisasi
- **Hero Slider:** ubah atau tambah slide di `.hero-slider` pada `index.html`. Pastikan file gambar baru dimasukkan ke `assets/img/` dan perbarui `alt` text.
- **Produk:** update konten kartu produk pada section `#produk`. Ganti `src`, nama produk, deskripsi, dan harga sesuai katalog terbaru.
- **Galeri:** tambahkan `<img>` baru di `.gallery-grid` untuk menampilkan foto tambahan.
- **Warna & Typografi:** semua warna/typography tersentral di variabel CSS pada bagian awal `style.css`. Mengubah `--primary-color`, `--secondary-color`, atau font akan langsung mempengaruhi seluruh halaman.
- **Alamat & Tahun Hak Cipta:** footer menyimpan alamat toko dan tahun berjalan. Sesuaikan teks di `index.html` jika ada perubahan.

## Dependensi
- [Google Fonts](https://fonts.google.com/) (Lora & Montserrat)
- [Ionicons](https://ionic.io/ionicons) untuk ikon navigasi

Keduanya dimuat via CDN langsung dari HTML, sehingga tidak memerlukan build step tambahan.

## Dukungan
Jika membutuhkan penyesuaian lebih lanjut (integrasi backend, form submission nyata, atau optimasi performa), tinggal tambahkan skrip/layanan tambahan di luar berkas ini. Silakan hubungi tim web Kopi Ratuku untuk arahan selanjutnya. Selamat menikmati kopi! ☕

