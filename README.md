# Chill Movie - Mission Intermediate 2FE B Implementasi (UseState & CRUD)

Aplikasi streaming film berbasis ReactJS. Dibuat sebagai bagian dari misi belajar implementasi `useState` dan manipulasi data array object (CRUD).

# Live demo site
(https://mission-2-fe-1-b-18101-zweta-tri-ra.vercel.app/)

## Fitur CRUD

CRUD diimplementasikan di dua section pada Homepage (sesuai instruksi misi boleh 1-2 fitur saja tidak menyeluruh):

```bash
- Film Trending   → Tambah, Lihat, Edit, Hapus film
- Rilis Baru      → Tambah, Lihat, Edit, Hapus film
```

## Implementasi useState

```bash
- filmTrending          → menyimpan data film trending
- rilsBaru              → menyimpan data rilis baru
- form                  → menyimpan input dari form
- modalOpen             → mengontrol buka/tutup modal form
- isEdit                → menentukan mode tambah atau edit
- selectedFilm          → menyimpan film yang sedang diedit
- konfirmasiOpen        → mengontrol buka/tutup modal hapus
- filmYangAkanDihapus   → menyimpan film yang akan dihapus
- toast                 → menampilkan notifikasi
```

## Operasi Array Object

```bash
GET    → films.map()               menampilkan semua data film
ADD    → [...filmTrending, baru]   menambah data baru ke array
UPDATE → filmTrending.map()        mengupdate data berdasarkan id
DELETE → filmTrending.filter()     menghapus data berdasarkan id
```
## Cara Menjalankan

```bash
git clone https://github.com/ZwetaTriRahma/Mission-2FE-1B---18101-Zweta-Tri-Rahma.git
cd chill-movie-react2
npm install
npm run dev
```
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
