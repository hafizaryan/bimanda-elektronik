# Bimanda Elektronik

Website profil dan katalog untuk Bimanda Elektronik, sebuah toko dan penyedia jasa solusi listrik. Website ini dibuat sebagai proyek Ujian Akhir Semester (UAS) mata kuliah Business Modeling berdasarkan studi kasus toko Bimanda Elektronik.

## Isi Website

- Halaman utama satu halaman (one page) dengan bagian:
  - Header dan banner "Solusi Listrik Terbaik"
  - Profil Toko dan layanan, di antaranya instalasi listrik dan layanan kelistrikan lainnya
  - Product, berisi daftar produk yang masing-masing memiliki halaman detail sendiri (`produk1.html` sampai `produk9.html`)
  - Contact Us, formulir kontak berbasis JavaScript dan tombol pesan WhatsApp
- Sembilan halaman detail produk statis
- Formulir kontak dengan validasi sisi klien (`contactform/contactform.js`)

## Teknologi

- HTML5 dan CSS3
- Bootstrap 3 (tema "Baker" dari BootstrapMade)
- JavaScript dan jQuery, bxSlider, Font Awesome, Animate.css, WOW.js
- Google Fonts (Roboto dan Raleway)

## Struktur Proyek

```
bimanda-elektronik/
├── contactform/     # Skrip formulir kontak (contactform.js)
├── css/             # bootstrap, font-awesome, bxslider, animate, style
├── fonts/           # Berkas font
├── img/             # Gambar produk dan ilustrasi layanan
├── js/              # Skrip JavaScript
├── index.html       # Halaman utama
├── produk1.html     # Halaman detail produk 1
├── ...
└── produk9.html     # Halaman detail produk 9
```

## Cara Menjalankan

Website ini statis dan tidak membutuhkan server khusus:

1. Clone repositori ini.
2. Buka `index.html` langsung di browser, atau jalankan server statis sederhana, misalnya:

   ```bash
   npx serve .
   # atau
   python -m http.server 8000
   ```

   lalu akses `http://localhost:8000`.

## Tim

Proyek ini dikerjakan oleh Hafiz Aryan Siregar, Pingki Muliya Susanti, dan Aditya Nugraha Yesa.

## Kredit

Tema dasar "Baker" oleh BootstrapMade.com.
