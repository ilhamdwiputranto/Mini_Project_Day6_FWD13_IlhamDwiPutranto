# Mini Project Full-Stack Web Development: DibiTech

**DibiTech** adalah sebuah platform marketplace produk digital modern yang menyediakan berbagai alat berbasis Artificial Intelligence (AI) seperti asisten penulisan, pembuat gambar, asisten pemrogram, dan analitik data.

Mini project ini dibuat sebagai pemahaman struktur HTML5 semantik, CSS3 modern dengan metodologi BEM, serta pengaplikasian _framework_ Tailwind CSS dan desain responsif.

---

## 📸 Tampilan Antarmuka

| Halaman                       | Deskripsi                                                                                              |
| :---------------------------- | :----------------------------------------------------------------------------------------------------- |
| **Home (HTML & CSS)**         | Berisi Landing Page utama yang dibuat menggunakan HTML5 Murni & CSS3 dengan BEM Naming (`index.html`). |
| **Katalog Produk (Tailwind)** | Berisi daftar produk digital AI yang dibuat menggunakan Tailwind CSS (`catalog.html`).                 |
| **Detail Produk (Tailwind)**  | Berisi informasi rinci fitur dan tombol pembelian produk (`detail-produk.html`).                       |
| **Keranjang & Checkout**      | Berisi alur transaksi dan ringkasan pembayaran (`cart.html` & `checkout.html`).                        |

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Menggunakan elemen semantik (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) untuk struktur web yang rapi dan _accessible_.
- **CSS3 Modern**:
  - Konsep Layouting: **Flexbox** dan **CSS Grid**.
  - Naming Convention: **BEM (Block Element Modifier)** pada file `style.css`.
  - Efek interaktif: Transition, transform, dan state `:hover` / `:focus`.
- **Tailwind CSS**:
  - Penggunaan Utility Classes untuk fleksibilitas styling.
  - Penerapan `@layer components` dan `@apply` untuk membuat kelas kustom yang dapat digunakan kembali (_reusable design_).
- **JavaScript (Vanilla)**:
  - Manipulasi DOM sederhana untuk toggle _mobile navigation menu_.

---

## 📁 Struktur Repositori

```text
.
├── index.html           # Assignment 1: Landing Page Murni (HTML + CSS)
├── style.css            # Custom CSS dengan BEM Metodologi
├── catalog.html         # Assignment 2: Katalog Produk (Tailwind CSS)
├── detail-product.html  # Explorasi: Halaman Detail Produk Digital
├── cart.html            # Explorasi: Halaman Keranjang Belanja
├── checkout.html        # Explorasi: Halaman Form Checkout & Pembayaran
├── images/              # Folder untuk aset gambar, ikon, dan screenshot
└── README.md            # Dokumentasi Project
```

---

## 🎯 Fitur & Keunggulan Desain

1. **Fully Responsive Layout**: Tampilan teroptimasi dengan baik di perangkat Mobile, Tablet, dan Desktop.
2. **Reusable Design System**: Konsistensi komponen tombol, kartu produk, dan navigasi di seluruh halaman web.
3. **Aksesibilitas Dasar**:
   - Struktur _Heading_ hierarkis dan teratur ($H1 \rightarrow H2 \rightarrow H3$).
   - Kontras warna yang seimbang untuk kenyamanan dibaca.
   - Atribut `alt` pada setiap gambar untuk pembaca layar (_screen reader_).

---

© 2026 **DibiTech** - Tugas Mini Project Full-Stack Web Development.
