# Dovimo — Room Planner UI

Implementasi front-end React + TypeScript + Vite yang mengikuti referensi mockup Dovimo.

## Menjalankan di komputer
1. Install Node.js versi 20 atau lebih baru.
2. Ekstrak file ZIP ini.
3. Buka terminal di folder `dovimo`.
4. Jalankan `npm install`
5. Jalankan `npm run dev`
6. Buka alamat lokal yang ditampilkan oleh Vite.

## Build / deploy
- `npm run build` menghasilkan folder produksi `dist/`.
- Upload folder `dist/` ke Vercel, Netlify, atau hosting statis lainnya.

## Fitur prototipe
- Layout responsif desktop dan mobile.
- Katalog furnitur dengan pencarian dan kategori.
- Klik furnitur untuk menambahkannya ke denah.
- Pilih objek lalu edit posisi, ukuran, rotasi, dan warna material.
- Toggle tampilan 2D / preview 3D bergaya.
- Kontrol zoom dan reset denah.
- Export susunan proyek sebagai file JSON.

## Catatan
Ini adalah prototipe front-end yang dibuat berdasarkan screenshot. Denah dan objek adalah elemen SVG/CSS ilustratif, bukan mesin CAD profesional. Drag-and-drop bebas, render 3D sesungguhnya, akun pengguna, penyimpanan cloud, serta riwayat undo/redo masih perlu dikembangkan.
