# WESST Fotocopy

Website sederhana untuk WESST Fotocopy (satu file `index.html`, tanpa instalasi).

## Cara upload ke GitHub

```bash
cd westt-fotocopy-print
git init
git add .
git commit -m "Website WESST Fotocopy"
git branch -M main
git remote add origin https://github.com/USERNAME/westt-fotocopy-print.git
git push -u origin main
```

Ganti `USERNAME` dengan username GitHub Anda (buat repository kosong dulu di github.com).

## Aktifkan website gratis (GitHub Pages)

1. Buka repository, lalu **Settings → Pages**.
2. Pada **Source**, pilih **Deploy from a branch**.
3. Pilih branch **main** dan folder **/ (root)**, lalu **Save**.
4. Tunggu 1–2 menit. Alamat web: `https://USERNAME.github.io/westt-fotocopy-print/`

## Mengubah harga atau kontak

Buka `index.html`, cari teks yang ingin diganti (misalnya `Rp 500` atau harga pada bagian Cetak foto), ubah, lalu:

```bash
git add .
git commit -m "Update harga"
git push
```

## File di dalam folder

- `index.html` – halaman website
- `logo.png` dan `favicon.png` – logo (harus satu folder dengan `index.html`)
- `README.md` – panduan ini
