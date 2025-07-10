# Nama: Meisyah Ababil 
# NPM: 233510092

# Be Bread
# TUGAS BESAR UAS PRAKTIKUM PEMOGRAMAN BERBASIS KOMPONEN

## 📝 Deskripsi
**Be Bread** adalah sebuah aplikasi web yang dirancang untuk menjadi platform pemesanan roti dan pastry secara online. Aplikasi ini bertujuan untuk memberikan pengalaman berbelanja yang mudah dan menyenangkan bagi pelanggan. Komponen **Footer** dari website ini adalah bagian penting yang memberikan informasi tambahan kepada pengguna mengenai toko, cara menghubungi, dan informasi penting lainnya.

Footer ini dirancang menggunakan **Vue.js** dan **Tailwind CSS**, yang memungkinkan tampilan yang responsif dan modern baik di perangkat desktop maupun mobile. Dengan desain yang bersih dan informatif, footer ini membantu pengguna untuk menemukan informasi yang mereka butuhkan dengan cepat.

## 📦 Fitur Utama
- **Informasi Perusahaan:** Menampilkan nama toko dan deskripsi singkat mengenai Be Bread, memberikan gambaran kepada pengguna tentang apa yang ditawarkan oleh toko.
- **Kontak Kami:**
  - **Nomor Telepon:** Memudahkan pelanggan untuk menghubungi toko jika mereka memiliki pertanyaan atau membutuhkan bantuan.
  - **Alamat Email:** Menyediakan cara bagi pelanggan untuk mengirimkan pertanyaan atau umpan balik melalui email.
  - **Alamat Fisik:** Memberikan informasi lokasi toko untuk pelanggan yang ingin berkunjung secara langsung.
- **Jam Operasional:** Menampilkan hari dan jam buka toko, sehingga pelanggan tahu kapan mereka dapat melakukan pemesanan atau mengunjungi toko.
- **Sosial Media:** 
  - Tautan ke akun **Facebook** dan **Instagram** Be Bread, memungkinkan pelanggan untuk mengikuti dan terhubung dengan toko melalui platform media sosial.
  - Ikon sosial media dirancang dengan gaya modern menggunakan SVG, memberikan tampilan yang menarik dan profesional.
- **Desain Responsif:** Menggunakan grid `md:grid-cols-4` dan layout `flex` untuk memastikan tampilan yang optimal di berbagai ukuran layar, dari smartphone hingga desktop.
- **Warna & Estetika:** Menggunakan palet warna yang sesuai dengan branding Be Bread, termasuk `bg-maroon-800` untuk latar belakang dan `text-white` untuk teks, menciptakan kontras yang baik dan meningkatkan keterbacaan.

## 📂 Struktur Kode
File ini disimpan di:  
`/src/components/Footer.vue`

### Struktur Utama:
- `<template>`: Bagian ini berisi HTML dan struktur visual dari komponen footer, termasuk elemen-elemen yang ditampilkan kepada pengguna.
- `<script>`: Bagian ini mengekspor komponen Vue, memungkinkan komponen ini digunakan di bagian lain dari aplikasi.
- **Tailwind CSS**: Digunakan untuk styling dan layout, memberikan fleksibilitas dalam desain dan memastikan bahwa komponen footer terlihat konsisten dengan elemen lain di aplikasi.

## 📄 Cara Menjalankan Aplikasi
1. Clone repositori ini ke mesin lokal Anda.
2. Jalankan perintah `npm install` untuk menginstal semua dependensi.
3. Jalankan perintah `npm run dev` untuk memulai server pengembangan.
4. Buka browser dan akses `http://localhost:3000` untuk melihat aplikasi.

Dengan penjelasan yang lebih lengkap ini, pembaca akan mendapatkan pemahaman yang lebih baik tentang proyek Anda, fitur-fitur yang ada, dan bagaimana cara menjalankannya. Jika ada bagian lain yang ingin Anda tambahkan atau ubah, silakan beri tahu!
## 🎥 Penjelasan Video
Untuk penjelasan detail implementasi dan per baris kode, bisa ditonton di video presentasi berikut yang telah saya buat:
[Link Video YouTube](https://youtu.be/85e8xj6j6lE)

## 🚀 Cara Menggunakan
1. Impor komponen `Footer.vue` ke dalam `App.vue` atau halaman utama.
2. Pastikan Tailwind sudah terpasang.
3. Gunakan seperti biasa:

```vue
<template>
  <Footer />
</template>

<script>
import Footer from './components/Footer.vue'

export default {
  components: { Footer }
}
</script>
