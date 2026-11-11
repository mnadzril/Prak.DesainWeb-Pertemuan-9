# Muhammad Nadzril Ilham Kusuma - 4525210084
# Selaras Coffee - One Page Website UMKM

Tugas pembuatan website profil UMKM satu halaman (*One Page Website*) menggunakan kerangka kerja Bootstrap 5 dan CSS kustom dengan tema warna bernuansa kopi (cokelat dan krem).

---

## Ringkasan Pengerjaan

Website UMKM *Selaras Coffee* dirancang dalam bentuk *One Page Website* menggunakan Bootstrap 5 dengan identitas visual bertema kopi. Komponen yang diimplementasikan meliputi navbar responsif dengan *hamburger toggle*, hero section informatif, notifikasi promo berbasis alert, tiga kartu produk, modal interaktif, formulir kontak terstruktur, serta footer penutup. Styling eksternal ditambahkan untuk memperkuat branding melalui efek interaksi kartu, aksen warna, dan palet yang serasi.

Selama proses perancangan, kendala yang dihadapi adalah komponen bawaan Bootstrap (seperti Card dan Navbar) yang seringkali terlihat kaku dan sama dengan *website template* pada umumnya. Selain itu, penyesuaian jarak antar elemen (*spacing*) pada *viewport* mobile sempat membuat form kontak dan hero section terasa terlalu padat.

Solusi yang diterapkan adalah menambahkan *Custom CSS* dengan *hover effect* (transformasi `translateY`) dan *shadow* spesifik pada kartu produk agar lebih interaktif. Untuk mengatasi masalah *layout* di tampilan mobile, sistem *grid column* (`col-md`) dan *utility classes* Bootstrap seperti `gap`, `padding`, dan `margin` (misalnya `p-4`, `g-4`) dimaksimalkan sehingga elemen tersusun rapi. Interaktivitas Modal dan Alert juga diimplementasikan langsung menggunakan atribut `data-bs` bawaan Bootstrap. Hasil akhir menghasilkan antarmuka yang bersih, fungsional, dan responsif.

---

## Checklist Kelengkapan Komponen

| No | Komponen Wajib | Implementasi pada Kode | Keterangan |
| :--- | :--- | :--- | :--- |
| 1 | Navbar Responsif | `<nav class="navbar navbar-expand-lg ...">` | Collapse ke hamburger menu di mobile |
| 2 | Hero Section | `<section id="beranda" class="hero-section ...">` | Headline utama + tombol *call-to-action* |
| 3 | Minimal 3 Card | 3 kartu menu (`.product-card`, `.col-md-4`) | Menampilkan menu andalan & harga |
| 4 | Minimal 1 Alert | Alert promo (`.alert .custom-alert .alert-dismissible`) | Notifikasi diskon yang bisa ditutup |
| 5 | Minimal 1 Modal | Modal popup (`#orderModal`) | Konfirmasi pemesanan ke WhatsApp |
| 6 | Form Kontak | Form input nama, email, dan textarea pesan | Formulir *inquiries* & pertanyaan |
| 7 | Footer | `<footer class="custom-footer ...">` dengan info toko | Penutup halaman bernuansa gelap |
| 8 | Custom CSS | `style.css` | Branding warna kopi & *hover effect* |

---

## Screenshot Output

### 1. Tampilan Desktop
<img width="2560" height="4086" alt="screenshot desktop" src="https://github.com/user-attachments/assets/cc33a839-a851-429f-98b0-4405338cf33a" />


### 2. Tampilan Mobile
<img width="1320" height="8895" alt="screenshot mobile" src="https://github.com/user-attachments/assets/5eab97c4-01e1-429d-b0ff-913685bae995" />


---

## Struktur Folder Project

```text
tugas-selaras-coffee/
├── index.html       # File HTML utama (struktur & komponen Bootstrap)
├── README.md        # Dokumentasi ringkasan dan panduan tugas
├── style.css        # Custom CSS eksternal (warna, hero, efek hover)
└── images/          # Folder untuk menyimpan screenshot (opsional)
    ├── screenshot-desktop.png
    └── screenshot-mobile.png
```

---

## Teknologi yang Digunakan

*   **HTML5:** Semantik struktur website.
*   **Bootstrap 5.3.2:** Framework CSS untuk *grid system*, *layout* responsif, dan komponen UI interaktif.
*   **Custom CSS3:** Pengaturan palet warna, tipografi, dan transisi visual.

---
