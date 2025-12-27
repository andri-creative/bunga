<div align="center">

# 🌸 Bunga - Animated Flower Gift

<img src="images/gift.png" width="120" alt="Gift Icon" />

### ✨ Hadiah Digital Interaktif dengan Animasi Bunga yang Indah

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/)

[Demo Live](#) • [Lapor Bug](../../issues) • [Request Fitur](../../issues)

</div>

---

## 📖 Tentang Proyek

**Bunga** adalah aplikasi web interaktif yang menampilkan animasi bunga yang indah dengan efek mengetik teks. Cocok untuk dijadikan hadiah digital romantis atau ucapan spesial kepada orang tersayang! 💝

### ✨ Fitur Utama

- 🎨 **Animasi CSS Murni** - Tidak ada library eksternal, performa optimal
- 🌙 **Latar Belakang Malam** - Suasana yang tenang dan romantis
- ⌨️ **Efek Mengetik** - Teks muncul dengan animasi typewriter
- 🎭 **Transisi Halus** - Animasi yang smooth dan menyenangkan
- 📱 **Responsive Design** - Tampil sempurna di semua perangkat
- 🎯 **Mudah Dikustomisasi** - Ubah teks dan pesan sesuai keinginan
- 🚀 **Ringan & Cepat** - Tanpa dependencies, load time minimal

---

## 🎬 Preview

> **Catatan:** Tambahkan screenshot atau GIF animasi di sini untuk menampilkan preview proyek

```
┌─────────────────────────────────┐
│   Halaman 1: Landing Page       │
│   • Judul animasi per huruf     │
│   • Tombol "Open" dengan efek   │
│   • Background malam bintang    │
└─────────────────────────────────┘
              ↓
┌─────────────────────────────────┐
│   Halaman 2: Flower Animation   │
│   • 3 bunga dengan animasi      │
│   • Rumput dan daun tumbuh      │
│   • Teks muncul bertahap        │
└─────────────────────────────────┘
```

---

## 📂 Struktur Proyek

```
bunga/
├── 📄 index.html          # Halaman pembuka dengan tombol
├── 📄 flower.html         # Halaman animasi bunga utama
├── 📁 css/
│   ├── index.css          # Styling halaman pembuka
│   └── style.css          # Styling & animasi bunga
├── 📁 js/
│   ├── index.js           # Animasi judul per huruf
│   └── main.js            # Kontrol animasi & typewriter
├── 📁 images/
│   └── gift.png           # Icon favicon
├── 📁 scss/
│   └── style.scss         # Source SCSS (opsional)
├── 📄 CNAME               # Custom domain GitHub Pages
└── 📄 README.md           # Dokumentasi ini
```

### 📋 Penjelasan File

| File | Deskripsi |
|------|-----------|
| `index.html` | 🏠 Entry point - halaman pembuka dengan animasi judul |
| `flower.html` | 🌺 Halaman utama dengan animasi bunga lengkap |
| `css/index.css` | 🎨 Styling untuk halaman pembuka |
| `css/style.css` | ✨ Styling & keyframe animasi bunga |
| `js/index.js` | 🔤 Script animasi judul per huruf dengan delay acak |
| `js/main.js` | ⚙️ Script pengendali animasi & efek mengetik |
| `images/` | 🖼️ Folder aset gambar (favicon, dll) |
| `scss/style.scss` | 📝 Source SCSS untuk kompilasi CSS (opsional) |

---

## 🚀 Cara Menggunakan

### Metode 1: Langsung di Browser (Paling Mudah)

1. **Clone repository** ini:
   ```bash
   git clone https://github.com/username/bunga.git
   cd bunga
   ```

2. **Buka file** `index.html` di browser favorit Anda
   - Double-click file `index.html`, atau
   - Drag & drop ke browser window

3. **Klik tombol "Open"** untuk melihat animasi bunga 🌸

### Metode 2: Menggunakan Local Server (Direkomendasikan)

Jika asset tidak terbaca atau ingin pengalaman lebih baik:

**Dengan VS Code + Live Server:**
```bash
1. Buka folder proyek di VS Code
2. Install extension "Live Server"
3. Klik kanan index.html → "Open with Live Server"
4. Browser akan otomatis terbuka di http://localhost:5500
```

**Dengan Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Akses di browser: http://localhost:8000
```

**Dengan Node.js:**
```bash
npx http-server -p 8000
# Akses di browser: http://localhost:8000
```

---

## 🎨 Kustomisasi

### Mengubah Teks Halaman Pembuka

Edit file `js/index.js`:
```javascript
// Ubah teks di baris ini
let text = 'I Have Something';  // ← Ganti dengan teks Anda
```

### Mengubah Pesan di Halaman Bunga

Edit file `js/main.js`:
```javascript
// Ubah pesan di baris ini
const titles = "I LOVE U";  // ← Ganti dengan pesan Anda
```

### Mengubah Warna Bunga

Edit file `css/style.css`, cari class `.flower__leafs` dan sesuaikan nilai `background`:
```css
.flower__leafs--1 {
  background: linear-gradient(to bottom, #ff6b9d, #c06c84);  /* Bunga 1 */
}

.flower__leafs--2 {
  background: linear-gradient(to bottom, #ffa07a, #ff6347);  /* Bunga 2 */
}

.flower__leafs--3 {
  background: linear-gradient(to bottom, #98d8c8, #6bcf7f);  /* Bunga 3 */
}
```

### Mengubah Kecepatan Animasi

Edit file `css/style.css`, sesuaikan nilai `animation-duration`:
```css
.flower {
  animation: grow 2s ease-in-out;  /* Ubah 2s menjadi lebih cepat/lambat */
}
```

---

## 🌐 Deploy ke GitHub Pages

1. **Push** kode ke repository GitHub Anda
2. Buka **Settings** → **Pages**
3. Pilih branch `main` dan folder `/ (root)`
4. Klik **Save**
5. Website akan live di `https://username.github.io/bunga`

### Custom Domain (Opsional)

Jika ingin menggunakan domain sendiri:
1. Edit file `CNAME` dengan domain Anda
2. Atur DNS domain ke GitHub Pages
3. Tunggu propagasi DNS (5-10 menit)

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur semantik modern
- **CSS3** - Animasi & styling dengan keyframes
- **JavaScript (Vanilla)** - Tanpa framework, murni JS
- **SCSS** - Preprocessor CSS (opsional)
- **GitHub Pages** - Hosting gratis

---

## 💡 Tips & Trik

- 🎯 **Gunakan di special occasions** - Ulang tahun, anniversary, valentine
- 📸 **Screenshot & share** - Bagikan ke social media
- 🎁 **Personalisasi pesan** - Buat lebih spesial dengan nama
- 🌈 **Eksperimen warna** - Sesuaikan dengan tema favorit
- 📱 **Test di mobile** - Pastikan tampil bagus di semua device

---

## 🤝 Kontribusi

Kontribusi sangat diterima! Jika Anda ingin berkontribusi:

1. Fork repository ini
2. Buat branch fitur (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -m 'Menambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

---

## 📝 Lisensi

Proyek ini bebas digunakan untuk keperluan pribadi dan komersial.

---

## 💖 Dibuat dengan Cinta

Jika proyek ini bermanfaat, jangan lupa beri ⭐ di repository!

<div align="center">

**[⬆ Kembali ke Atas](#-bunga---animated-flower-gift)**

---

Made with 💐 and ☕

</div>
