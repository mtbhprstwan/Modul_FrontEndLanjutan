# Bab 2: Tailwind CSS

## Pendahuluan
Tailwind CSS adalah framework CSS modern yang mengusung pendekatan **utility-first**.
Alih-alih menulis CSS kustom dalam jumlah besar, Tailwind menyediakan class utilitas
kecil yang dapat langsung digunakan di HTML atau JSX/TSX untuk membangun UI
dengan cepat, konsisten, dan mudah dipelihara.

Pendekatan ini sangat cocok untuk pengembangan frontend modern berbasis komponen
seperti React, Next.js, dan Vue.

---

## Tujuan Pembelajaran
Setelah mempelajari bab ini, mahasiswa diharapkan mampu:
- Memahami konsep utility-first CSS
- Menggunakan Tailwind CSS untuk styling UI
- Membangun tampilan responsif dengan pendekatan mobile-first
- Menerapkan component-based styling
- Mengikuti best practices dalam penggunaan Tailwind CSS

---

## 1. Utility-first CSS

### Konsep Dasar
Utility-first CSS adalah pendekatan styling di mana setiap class memiliki satu
tanggung jawab spesifik, seperti mengatur:
- Spacing (margin, padding)
- Warna
- Typography
- Layout

Pendekatan ini berbeda dengan CSS konvensional yang mengandalkan class kustom
dan file CSS terpisah.

### Contoh Penggunaan
```html
<div class="p-4 bg-blue-500 text-white rounded-lg">
  Hello Tailwind
</div>
