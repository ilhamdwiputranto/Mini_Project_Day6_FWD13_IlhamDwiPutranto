# Mini Project Full-Stack Web Development: DibiTech

**DibiTech** adalah sebuah platform marketplace produk digital modern yang menyediakan berbagai alat berbasis Artificial Intelligence (AI) seperti asisten penulisan, pembuat gambar, asisten pemrogram, dan analitik data.

Mini project ini dibuat sebagai pemahaman struktur HTML5 semantik, CSS3 modern dengan metodologi BEM, serta pengaplikasian _framework_ Tailwind CSS dan desain responsif.

---

## 📸 Tampilan Antarmuka

| Halaman                              | Deskripsi                                                                                                               |
| :----------------------------------- | :---------------------------------------------------------------------------------------------------------------------- |
| **Home (HTML & CSS)**                | Berisi Landing Page utama yang dibuat menggunakan HTML5 Murni & CSS3 dengan BEM Naming (`index.html`).                  |
| **Login, Katalog Produk (Tailwind)** | Berisi halaman login dan daftar produk digital AI yang dibuat menggunakan Tailwind CSS (`Login.html` & `catalog.html`). |
| **Detail Produk (Tailwind)**         | Berisi informasi rinci fitur dan tombol pembelian produk (`detail-produk.html`).                                        |
| **Keranjang & Checkout**             | Berisi alur transaksi dan ringkasan pembayaran (`cart.html` & `checkout.html`).                                         |

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Menggunakan elemen semantik (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) untuk struktur web yang rapi dan _accessible_.
- **CSS3 Modern**:
  - Konsep Layouting: **Flexbox** dan **CSS Grid**.
  - Naming Convention: **BEM (Block Element Modifier: "block\_\_element--modifier")** pada file `style.css`.
  - Efek interaktif: Transition, transform, dan state `:hover` / `:focus`.
- **Tailwind CSS**:
  - Penggunaan Utility Classes.
  - Penerapan `@layer components` dan `@apply` untuk membuat kelas kustom yang dapat digunakan kembali (_reusable design_).
- **JavaScript (Vanilla)**:
  - Eksplorasi untuk manipulasi untuk toggle _mobile navigation menu_.

---

## 📁 Struktur Repositori

```text
.
├── index.html           # Assignment 1: Landing Page Murni (HTML + CSS)
├── style.css            # Custom CSS dengan BEM Metodologi
├── login.html         # Assignment 2: Login (Tailwind CSS)
├── catalog.html         # Assignment 2: Katalog Produk (Tailwind CSS)
├── detail-product.html  # Assignment 2: Halaman Detail Produk Digital (Tailwind CSS)
├── cart.html            # Assignment 2: Halaman Keranjang Belanja (Tailwind CSS)
├── checkout.html        # Assignment 2: Halaman Form Checkout & Pembayaran (Tailwind CSS)
├── images/              # Folder untuk aset gambar, dan ikon
└── README.md            # Dokumentasi Project
```

---

## 🎯 Fitur & Desain

1. **Fully Responsive Layout**: Tampilan teroptimasi di perangkat Mobile, Tablet, dan Desktop.
2. **Reusable Design System**: Konsistensi komponen tombol, kartu produk, dan navigasi di seluruh halaman web.
3. **Aksesibilitas Dasar**:
   - Struktur hierarkis dan teratur.
   - Kontras warna yang seimbang untuk kenyamanan dibaca.
   - Atribut `alt` pada setiap gambar untuk pembaca layar (_screen reader_).

---

© 2026 **DibiTech** - Tugas Mini Project Full-Stack Web Development.
