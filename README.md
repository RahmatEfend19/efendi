# Portofolio — Rahmat Efendi

Portofolio statis (HTML + Tailwind CDN) untuk Rahmat Efendi, desainer visual.

## Isi folder
- `index.html` — halaman utama
- Gambar aset: `foto-.jpeg`, `1.png`–`3.png`, `karakter-*.png`, `mockup-*.png`, `belakang.png`, `depan-01.png`, `kopi-logo.png`, `poster interior.png`

## Menjalankan lokal
Buka `index.html` langsung di browser, atau jalankan server statis:

```sh
# Python 3
python -m http.server 8000
# lalu buka http://localhost:8000
```

## Upload ke GitHub
1. Buat repository baru di GitHub (mis. `portofolio`).
2. Upload semua file di folder ini (atau `git push`).
3. Pastikan `index.html` berada di root repository.

## Aktifkan GitHub Pages
1. Repository → **Settings** → **Pages**.
2. Source: **Deploy from a branch** (atau **GitHub Actions**).
3. Branch: `main` / root (`/`).
4. Tunggu beberapa menit, lalu akses `https://<username>.github.io/<repo>/`.

> Catatan: path gambar bersifat relatif, jadi aman untuk GitHub Pages. Nama file bersifat case-sensitive di Pages.