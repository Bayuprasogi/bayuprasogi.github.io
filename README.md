# Portofolio Dimas Bayu Prasogi

Situs satu halaman. Semua isi ada di `index.html`, gambar proyek di `img/`.

Tayang di **https://bayuprasogi.github.io**

## Isi halaman
- **Awal**: helai garis biru yang mengalir, kubus kaca berisi `</>` dengan garis penghubung ke alat kerja (Three.js).
- **Tentang**: ringkasan dan daftar centang.
- **Proyek**: ruang biru 3D. Karya melayang dan kamera terbang maju saat di-scroll.
- **Pengalaman**: lima pekerjaan, kata besar menyala satu per satu.
- **Bukan baru mulai**, **Tanya jawab**, dan **Kontak** (penutup biru).

## Mengganti isi
- Teks: buka `index.html` dan cari teks yang mau diganti.
- Karya di ruang Proyek: ubah daftar `items` di skrip "ruang proyek" dekat akhir file.
- Label di sekitar kubus: ubah `<div class="nodes">` di bagian awal (urutannya sama dengan titik di `NODES`).
- CV: taruh `cv.pdf` di folder ini, lalu ganti tulisan "CV menyusul" di bagian Kontak menjadi link ke `cv.pdf`.

## Memperbarui situs
Setelah mengubah file, jalankan:
```
git add .
git commit -m "Perbarui isi portofolio"
git push
```
GitHub Pages memperbarui situs dalam 1–2 menit.

## Catatan
- Pustaka dari CDN: Three.js r134, GSAP 3.12.5 + ScrollTrigger, Lenis 1.1.13, Motion 11.11.13.
- Kalau browser tidak mendukung WebGL, bagian Proyek tampil sebagai kartu biasa.
- Animasi berkurang otomatis untuk pengguna yang mengaktifkan "reduce motion".
