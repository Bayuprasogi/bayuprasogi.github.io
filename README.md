# Portofolio Dimas Bayu Prasogi

Situs satu halaman bergaya jendela aplikasi dengan scene 3D (Three.js). Semua isi ada di `index.html`.

Tayang di **https://bayuprasogi.github.io**

## Mengganti isi
Buka `index.html`, cari komentar `<!-- PROFIL -->`, `<!-- PENGALAMAN -->`, `<!-- PORTOFOLIO -->`, `<!-- TOOLS -->`, `<!-- TENTANG -->`, lalu ganti teksnya.
- CV: taruh `cv.pdf` di folder ini, lalu ikuti petunjuk di komentar dekat tombol "CV menyusul".

## Memperbarui situs
Setelah mengubah file, jalankan:
```
git add .
git commit -m "Perbarui isi portofolio"
git push
```
GitHub Pages memperbarui situs dalam 1–2 menit.

## Catatan
- Tiap tab punya alamat sendiri, misalnya `#portofolio`, jadi bisa dibagikan langsung.
- Kalau browser tidak mendukung WebGL, halaman tetap jalan dengan latar biasa.
- Animasi berkurang otomatis untuk pengguna yang mengaktifkan "reduce motion".
