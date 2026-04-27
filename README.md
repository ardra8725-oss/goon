# 🔴 XII.9 Gooners — Kenangan Kelas
Web memorial kelas XII.9 SMAN 12 Tangsel 2026

## 📁 Struktur Folder

```
repo/
├── index.html               ← File utama web
├── README.md
└── assets/
    └── img/
        ├── hero.jpg          ← Foto background hero (halaman utama)
        ├── zaky.jpg          ← Foto Leader (Zaky)
        ├── rafa.jpg          ← Foto Co-Leader (Rafa)
        ├── students/
        │   ├── ardra.jpg
        │   ├── fawwaz.jpg
        │   ├── fiqri.jpg
        │   ├── maulana.jpg
        │   ├── aufar.jpg
        │   ├── fachri.jpg
        │   ├── raja.jpg
        │   ├── rifat.jpg
        │   ├── yusril.jpg
        │   └── zacky.jpg
        └── gallery/
            ├── foto1.jpg
            ├── foto2.jpg
            ├── foto3.jpg
            ├── foto4.jpg
            ├── foto5.jpg
            ├── foto6.jpg
            ├── foto7.jpg
            ├── foto8.jpg
            ├── foto9.jpg
            ├── foto10.jpg
            ├── foto11.jpg
            ├── foto12.jpg
            ├── foto13.jpg
            ├── foto14.jpg
            └── video1.mp4
```

## 📸 Cara Isi Foto

### Foto Hero (background utama)
Upload foto ke `assets/img/hero.jpg`

### Foto Leader & Co-Leader
Upload ke `assets/img/zaky.jpg` dan `assets/img/rafa.jpg`
Lalu di `index.html` cari komentar `📸 GANTI DENGAN` dan ikuti instruksinya

### Foto Siswa
Upload ke `assets/img/students/namasiswa.jpg`
Lalu di `index.html` cari bagian `DATA SISWA` dan isi field `photo`:
```js
{ name:"ARDRA ...", photo:"assets/img/students/ardra.jpg", ... }
```

### Foto Galeri
Upload ke `assets/img/gallery/foto1.jpg` dst
Lalu di `index.html` cari `.g-item` dan isi `data-src` + tambah tag `<img>`

## 🚀 Cara Deploy ke GitHub Pages
1. Buat repo baru di GitHub (nama bebas, misal `kenangan-kelas`)
2. Upload semua file & folder ini ke repo
3. Buka **Settings → Pages**
4. Source: pilih **main branch → / (root)**
5. Klik **Save**
6. Web bisa diakses di: `https://username.github.io/kenangan-kelas`
