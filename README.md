# Undangan-Bootsrap5
Membuat Undangan Digital Menggunakan Bootsrap

# 💍 Himmel & Frieren Wedding Invitation

![Project Banner](img/bg1.jpg) > *“Perjalanan Sepuluh Tahun, Mengubah Arti Keabadian.”*

Website undangan pernikahan digital (undangan online) yang responsif dan estetis, dirancang dengan tema anime **Frieren: Beyond Journey's End** (Sousou no Frieren). Proyek ini dibangun menggunakan **Bootstrap 5** dan **Vanilla JavaScript**.

[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple?style=for-the-badge&logo=bootstrap)](https://getbootstrap.com/)
[![HTML5](https://img.shields.io/badge/HTML-5-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS-3-blue?style=for-the-badge&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JS-ES6-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## ✨ Fitur Utama

Website ini dilengkapi dengan berbagai fitur interaktif untuk tamu undangan:

* **📱 Responsif Penuh:** Tampilan menyesuaikan dengan sempurna di Mobile, Tablet, dan Desktop.
* **⏳ Countdown Timer:** Hitung mundur waktu acara menggunakan `simplyCountdown.js`.
* **💌 Custom Nama Tamu:** Mendukung parameter URL untuk personalisasi nama tamu (Contoh: `?n=NamaTamu`).
* **📍 Integrasi Peta:** Embed Google Maps untuk lokasi akad dan resepsi.
* **📝 RSVP via Google Sheets:** Formulir konfirmasi kehadiran yang terhubung langsung ke Google Sheets (tanpa backend server).
* **💬 Buku Tamu (Disqus):** Fitur komentar/ucapan selamat menggunakan layanan Disqus.
* **🎵 Audio Player:** Musik latar (Auto-play dengan tombol kontrol) untuk membangun suasana.
* **📜 Story Timeline:** Bagian cerita perjalanan cinta dengan desain timeline vertikal.
* **🖼️ Galeri Foto:** Lightbox galeri untuk menampilkan foto pre-wedding.
* **🎁 Amplop Digital:** Informasi nomor rekening/dompet digital.

## 🛠️ Teknologi yang Digunakan

* **Framework CSS:** [Bootstrap 5.3](https://getbootstrap.com/)
* **Icon:** [Bootstrap Icons](https://icons.getbootstrap.com/)
* **Font:** Google Fonts (Sacramento & Work Sans)
* **Library JS:**
    * `simplyCountdown.js` (Hitung mundur)
    * `bs5-lightbox` (Galeri popup)
* **Backend (Serverless):** Google Apps Script (untuk form RSVP)

## 📂 Struktur Folder

```text
├── audio/
│   └── blue.mp3           # File musik latar
├── countdown/             # Library simplyCountdown
├── img/                   # Aset gambar (background, foto couple, galeri)
├── style.css              # Custom CSS
├── index.html             # File utama
└── README.md              # Dokumentasi
