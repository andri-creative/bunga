# Bunga — HTML/CSS/JS

<p align="center">
  <img src="images/gift.png" width="96" alt="gift" />
</p>

<p align="center">
  Web statis 2 halaman: pembuka + animasi bunga dengan teks yang muncul bertahap.
</p>

## Isi Utama
- Halaman pembuka: `index.html` (tombol menuju halaman bunga)
- Halaman animasi: `flower.html` (animasi + teks mengetik)

## Struktur Proyek

| Lokasi | Fungsi |
|---|---|
| `index.html` | Entry halaman awal |
| `flower.html` | Halaman animasi bunga |
| `css/index.css` | Style halaman awal |
| `css/style.css` | Style + animasi halaman bunga |
| `js/index.js` | Membentuk judul per huruf + delay animasi acak |
| `js/main.js` | Memicu animasi + mengetik teks judul |
| `images/` | Aset gambar (favicon) |
| `scss/style.scss` | Sumber SCSS (opsional) |
| `CNAME` | Domain custom GitHub Pages (jika dipakai) |

## Cara Pakai (Lokal)

**Cara cepat**
1. Buka `index.html` di browser.
2. Klik tombol **Open** untuk ke `flower.html`.

**Kalau asset tidak kebaca**
- Jalankan lewat server lokal (contoh: Live Server di VS Code), lalu akses `index.html`.

## Kustomisasi Teks

- Judul halaman awal: ubah `text = 'I Have Something'` di `js/index.js`
- Teks di halaman bunga: ubah `const titles = "I LOVE U"` di `js/main.js`

## Cara Clone

```bash
git clone <url-repo>
cd <folder-repo>
```

Lalu buka `index.html` di browser (atau jalankan via Live Server).
