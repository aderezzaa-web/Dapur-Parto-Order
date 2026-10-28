# Dapur Parto: web app pesan

Halaman pesan Dapur Parto. Pembeli memilih menu, mengisi keranjang, lalu pesanan terkirim ke WhatsApp 0899-4632-174.

## Pasang di GitHub Pages (gratis)

1. Buat repository baru di GitHub, misalnya `dapur-parto`, atur jadi **Public**.
2. Ekstrak ZIP ini, lalu upload **semua isinya** (`index.html`, `manifest.json`, `sw.js`, `README.md`, dan folder `icons`) lewat *Add file → Upload files*, lalu *Commit changes*.
3. Buka *Settings → Pages*. Pilih *Deploy from a branch*, branch `main`, folder `/ (root)`, lalu *Save*.
4. Tunggu 1–2 menit. Link-nya muncul di halaman yang sama, misalnya `https://namakamu.github.io/dapur-parto/`.

## Pasang di layar utama HP

- Android (Chrome): buka link-nya, ketuk menu ⋮ lalu *Tambahkan ke layar utama* atau *Instal aplikasi*.
- iPhone (Safari): ketuk tombol bagikan, lalu *Tambahkan ke Layar Utama*.

## Mengubah isi

Harga, menu dan teks ada di `index.html`. Setelah mengganti file itu, buka `sw.js` dan naikkan versinya
(`dapur-parto-v1` jadi `dapur-parto-v2`), supaya HP pembeli mengambil versi terbaru.
