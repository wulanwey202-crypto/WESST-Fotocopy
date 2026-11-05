# WESST Fotocopy

Website sederhana untuk WESST Fotocopy (satu file `index.html`, tanpa instalasi).

Alamat web: https://wulanwey202-crypto.github.io/WESST-Fotocopy/

## Isi repository (semua harus di halaman depan repository, bukan di dalam folder)

- `index.html` – halaman website (nama harus persis begini, huruf kecil)
- `logo.png` dan `favicon.png` – logo (harus satu tempat dengan `index.html`)
- `README.md` – panduan ini

## Cara upload lewat GitHub (tanpa Git)

1. Buka repository `WESST-Fotocopy` di github.com.
2. Klik **Add file → Upload files**.
3. Seret **isi** folder website (bukan foldernya) ke halaman itu: `index.html`, `logo.png`, `favicon.png`.
4. Klik **Commit changes**.

## Cara upload lewat Git

```bash
cd folder-website-anda
git init
git add .
git commit -m "Website WESST Fotocopy"
git branch -M main
git remote add origin https://github.com/wulanwey202-crypto/WESST-Fotocopy.git
git push -u origin main
```

## Aktifkan website gratis (GitHub Pages)

1. Buka repository, lalu **Settings → Pages**.
2. Pada **Source**, pilih **Deploy from a branch**.
3. Pilih branch **main** dan folder **/ (root)**, lalu **Save**.
4. Tunggu 1–2 menit, lalu buka alamat web di atas dan tekan `Ctrl + F5`.

## Kalau yang tampil malah isi README ini

GitHub Pages menampilkan README bila tidak menemukan `index.html` di root. Cek:

- `index.html` terlihat langsung di halaman depan repository, bukan di dalam folder.
- Namanya bukan `Index.html`, `index.html.txt`, atau `index (1).html`. Di Windows, aktifkan **View → Show → File name extensions** untuk memastikan.

## Mengubah harga atau kontak

Buka `index.html`, cari teks yang ingin diganti (harga ada di daftar `P` pada bagian `<script>`, misalnya `p:500`), ubah, lalu commit.
