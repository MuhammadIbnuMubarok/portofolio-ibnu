# Portofolio Ibnu

Website statis ini disiapkan untuk GitHub Pages. File yang akan dipublikasikan saja berada di folder `site`; file sumber dan catatan lain tidak ikut tayang.

## Publikasi ke GitHub Pages

1. Buat repository baru di GitHub dengan nama `portofolio-ibnu`.
2. Unggah `site/index.html`, `site/favicon.svg`, dan `site/.nojekyll` ke dalam folder `site` pada repository.
3. Unggah `.github/workflows/pages.yml` ke lokasi yang sama di repository: `.github/workflows/pages.yml`.
4. Pastikan branch utama bernama `main`.
5. Di repository, buka **Settings → Pages** dan pilih **GitHub Actions** sebagai sumber deployment.
6. Tunggu workflow **Deploy static site to GitHub Pages** selesai.
7. Link publik biasanya berbentuk `https://NAMA-USER.github.io/portofolio-ibnu/`.

Jika nama repository bukan `portofolio-ibnu`, ganti bagian URL terakhir dengan nama repository yang dipilih.

## Struktur repository yang dibutuhkan

```text
.github/
  workflows/
    pages.yml
site/
  .nojekyll
  favicon.svg
  index.html
```

Website tidak memerlukan build step atau dependensi tambahan.
