# 📦 Aplikasi Daftar Produk (Fullstack Laravel + Vue)

Project ini adalah aplikasi web sederhana untuk menampilkan daftar produk dengan fitur pencarian, pengurutan (sorting), dan pagination. Aplikasi ini dibangun menggunakan arsitektur **Decoupled** (Terpisah), di mana Laravel berperan sebagai Backend API dan Vue.js sebagai Frontend.

## 🚀 Teknologi yang Digunakan

**Backend:**
* **Laravel 11** (API Framework)
* **MySQL** (Database)
* **PHP**

**Frontend:**
* **Vue.js 3** (JavaScript Framework)
* **Vite** (Build Tool)
* **Tailwind CSS 4.0** (Styling)
* **Axios** (HTTP Client)

---

## 🛠️ Fitur Utama

1.  **Server-Side Filtering:** Pencarian data (Nama Produk / Kategori) dilakukan langsung di database.
2.  **Server-Side Sorting:** Pengurutan harga (Termurah/Termahal) dilakukan oleh Query Builder Laravel.
3.  **Manual Pagination:** Menggunakan logika `OFFSET` dan `LIMIT` untuk membagi halaman data.
4.  **Responsive UI:** Tampilan tabel yang rapi di Desktop maupun Mobile (Card Layout).
5.  **Real-time Interaction:** Menggunakan Vue Watcher untuk update data otomatis saat filter berubah.

---

