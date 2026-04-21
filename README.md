# 🤍 Untuk Kamu - Website Kenangan

Website interaktif yang elegan untuk mengabadikan momen-momen spesial. Didesain responsif untuk semua perangkat termasuk mobile dan Android.

## 📋 Daftar File

```
surat/
├── kenangan.html          # File utama website
├── music.mp3             # File musik background
├── foto.png              # Foto slide 1
├── foto1.jpg             # Foto slide 2
├── foto2.jpg             # Foto slide 3
├── foto3.jpg             # Foto slide 4
├── foto4.png             # Foto slide 5
├── foto5.png             # Foto slide 5 (alternatif)
└── README.md             # File dokumentasi ini
```

## ✨ Fitur Utama

✅ **Autoplay Musik** - Musik dimulai otomatis saat halaman dibuka  
✅ **Gallery Slider** - Slider foto dengan navigasi dot dan tombol panah  
✅ **Animasi Hujan** - Rain effect di background (optimized untuk mobile)  
✅ **Responsive Design** - Sempurna di desktop, tablet, dan mobile  
✅ **Scroll Animations** - Animasi muncul saat scroll  
✅ **Line-by-line Poetry** - Puisi muncul baris demi baris  

## 🚀 Persiapan Hosting

### 1. **Persyaratan Server**
- Hosting dengan support HTTP/HTTPS (sebagian besar hosting gratis sudah support)
- Domain (opsional, bisa pakai subdomain hosting)
- Ukuran storage minimal: 50MB

### 2. **Upload ke Hosting**
1. Hubungkan ke hosting via FTP client (FileZilla, WinSCP, dll)
2. Upload semua file ke folder public_html atau root directory
3. Akses website via domain Anda

### 3. **Rekomendasi Hosting Gratis**
- **Netlify** - Upload langsung atau connect GitHub (recommended)
- **Vercel** - Cocok untuk static sites
- **GitHub Pages** - Gratis dengan GitHub account
- **InfinityFree** - Hosting gratis dengan cPanel
- **000webhost** - Hosting gratis dengan domain gratis

## 🛠️ Cara Menggunakan

### **Mengubah Konten:**

1. **Edit Judul & Teks Opening**
   ```html
   <h1 class="opening-title">Ganti Judul Disini</h1>
   <p class="opening-sub">Ganti subtitle disini</p>
   ```

2. **Menambah/Mengubah Foto Slider**
   - Ganti path `src="foto.png"` dengan nama file foto Anda
   - Tambah slide baru dengan copy-paste template slide
   - Update counter (1/5 menjadi 1/6 dst) dan dots

3. **Mengubah Nama di Section Puisi**
   ```html
   <h2 class="nama-title">Nama Orang</h2>
   <p class="nama-sub">Subtitle nama</p>
   ```

4. **Mengganti Musik**
   - Rename musik Anda menjadi `music.mp3`
   - Upload ke folder yang sama

5. **Edit Pesan & Puisi**
   - Ubah teks di section "PESAN" dan "PUISI"
   - Ganti penutup dengan nama/ucapan Anda

### **Edit CSS (Styling)**

Edit di dalam tag `<style>` di bagian `<head>`:

- **Warna tema**: Ubah variable di `:root`
  ```css
  :root {
    --black: #080808;        /* Warna background utama */
    --white: #f0ece4;        /* Warna text utama */
    --cream: #d8d0c4;        /* Warna accent */
  }
  ```

- **Font size**: Gunakan `clamp()` untuk responsive
  ```css
  font-size: clamp(1rem, 2.5vw, 1.3rem);
  /* min 1rem, preferred 2.5% viewport width, max 1.3rem */
  ```

## 📱 Kompatibilitas

- ✅ Desktop (Windows, Mac, Linux)
- ✅ Tablet (iPad, Android tablet)
- ✅ Mobile (iPhone, Android)
- ✅ Browser: Chrome, Firefox, Safari, Edge, Opera

## 🎵 Catatan Musik

- **Format**: MP3 (recommended)
- **Ukuran**: Maksimal 5MB (untuk loading cepat)
- **Durasi**: Ideal 3-5 menit (akan loop)
- **Volume**: Sudah diatur 28% (aman untuk telinga)

## ⚙️ Optimasi untuk Hosting

✅ Semua asset sudah dioptimasi  
✅ Responsive design untuk semua ukuran  
✅ Loading performance sudah optimal  
✅ Safe area support untuk notch devices  
✅ Cross-browser compatibility  

## 🔍 SEO & Meta Tags

Untuk mengoptimalkan di search engine, edit di `<head>`:

```html
<title>Judul Website - Untuk Ditampilkan di Browser</title>
<meta name="description" content="Deskripsi singkat website Anda">
```

## 📞 Troubleshooting

**Musik tidak diputar?**
- Pastikan file `music.mp3` sudah ada di folder yang sama
- Cek browser permissions untuk audio
- Coba refresh page

**Foto tidak muncul?**
- Pastikan nama file foto sesuai (case-sensitive di Linux hosting)
- Format gambar harus `.png`, `.jpg`, atau `.jpeg`
- Ukuran file tidak terlalu besar (max 2MB per foto)

**Website lambat?**
- Kompres foto dengan tools online (TinyPNG, Compressor.io)
- Gunakan format WebP untuk gambar lebih modern
- Minimalkan CSS/JS jika perlu

## 📝 Struktur HTML

```html
<!-- Section 1: OPENING -->
<!-- Section 2: GALLERY (Slider foto) -->
<!-- Section 3: PUISI -->
<!-- Section 4: PESAN -->
<!-- Section 5: PENUTUP -->
```

## 💡 Tips & Tricks

1. **Customize Warna**: Edit `:root` di CSS untuk theme baru
2. **Tambah Animasi**: Modifikasi `@keyframes` di CSS
3. **Ganti Font**: Edit link di Google Fonts
4. **Update Captions**: Ganti text di `.slide-caption p`
5. **Mobile Testing**: Gunakan Chrome DevTools (F12 → Toggle device)

## 📄 License

Website ini bebas digunakan dan dimodifikasi untuk keperluan pribadi.

## 🎨 Credits

- Fonts: Google Fonts (Playfair Display, Cormorant Garamond, EB Garamond)
- Stock Photos: Unsplash
- Design & Development: Custom

---

**Dibuat dengan ❤️ untuk momen-momen spesial**

*Last Updated: April 22, 2026*
