# 🚚 Wuzz - Jasa Pindahan Profesional

Wuzz adalah platform digital untuk layanan pindahan rumah dan kantor yang modern, aman, dan terpercaya. Kami menyediakan solusi pindahan yang mudah dan efisien dengan harga transparan.

![Wuzz](img/wuzz.png)

## 📋 Daftar Isi

- [Fitur Utama](#fitur-utama)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)
- [Struktur Proyek](#struktur-proyek)
- [Cara Menggunakan](#cara-menggunakan)
- [Fitur Layanan](#fitur-layanan)
- [Dokumentasi API](#dokumentasi-api)
- [Kontribusi](#kontribusi)
- [Kontak](#kontak)

## ⭐ Fitur Utama

### 1. **Kalkulator Biaya Otomatis**
   - Hitung estimasi biaya pindahan secara real-time
   - Berdasarkan volume barang dan jarak tempuh
   - Pilihan layanan dari yang ekonomis hingga express

### 2. **Request Pindahan Online**
   - Formulir lengkap untuk membuat request pindahan
   - Konfirmasi otomatis via email
   - Tracking status pindahan secara real-time

### 3. **Antarmuka Responsif**
   - Desain modern dan profesional
   - Kompatibel dengan semua perangkat (mobile, tablet, desktop)
   - Loading cepat dan performa optimal

### 4. **Dashboard Layanan**
   - Statistik real-time (cabang, pelanggan, pindahan aktif)
   - Informasi lengkap tentang layanan kami
   - Testimoni dan rating dari pelanggan

### 5. **Kontak 24/7**
   - Form kontak langsung di website
   - Hubungi via WhatsApp, email, atau telepon
   - Tim customer service siap membantu

## 🛠️ Teknologi yang Digunakan

### Frontend
- **HTML5** - Struktur semantic
- **CSS3** - Styling modern dengan gradients dan animations
- **Bootstrap 5.3.2** - Framework responsive
- **JavaScript Vanilla** - Interaktivitas tanpa dependencies berat

### Libraries & Tools
- **AOS (Animate On Scroll)** - Animasi elemen saat scroll
- **Google Fonts** - Font berkualitas (Poppins, Sora)
- **Icofont** - Icon library
- **Responsive Design** - Mobile-first approach

### Browser Support
- Chrome (terbaru)
- Firefox (terbaru)
- Safari (terbaru)
- Edge (terbaru)

## 📁 Struktur Proyek

```
wuzz.io/
├── index.html              # Halaman utama
├── css/
│   ├── style.css          # Stylesheet custom
│   └── icofont.css        # Icon library
├── fonts/                 # Custom fonts
├── img/                   # Gambar dan assets
│   ├── wuzz.png
│   ├── wuzz.jpg
│   ├── carousel1.jpg
│   ├── carousel2.jpg
│   ├── carousel3.jpg
│   └── Wuzz-logos_white.png
├── toyota.csv             # Data contoh
├── README.md              # Dokumentasi
└── .git/                  # Repository git
```

## 🚀 Cara Menggunakan

### Persyaratan
- Browser modern dengan JavaScript enabled
- Koneksi internet stabil
- Resolusi minimal 320px (mobile)

### Instalasi Lokal

1. **Clone repository**
   ```bash
   git clone https://github.com/username/wuzz.io.git
   cd wuzz.io
   ```

2. **Buka file**
   - Buka `index.html` langsung di browser, atau
   - Gunakan local server:
   ```bash
   # Jika Anda memiliki Python
   python -m http.server 8000
   
   # Atau gunakan Node.js
   npx http-server
   ```

3. **Akses website**
   - Buka `http://localhost:8000` di browser Anda

## 💼 Fitur Layanan

### 1. Layanan Reguler
- **Estimasi Waktu**: 5-7 hari
- **Harga Dasar**: Volume × Rp 1.000.000 + Jarak × Rp 50.000
- **Cocok untuk**: Pindahan lokal dan antar kota

### 2. Layanan Express
- **Estimasi Waktu**: 2-3 hari
- **Multiplier**: 1.35x dari harga dasar
- **Cocok untuk**: Pindahan urgent

### 3. Layanan Overnight
- **Estimasi Waktu**: Hari yang sama
- **Multiplier**: 1.70x dari harga dasar
- **Cocok untuk**: Pindahan sangat mendesak

## 📊 Dokumentasi Fitur

### Kalkulator Biaya

```javascript
// Formula perhitungan
totalCost = (volume × Rp1.000.000 + distance × Rp50.000) × serviceMultiplier

// Contoh:
- Volume: 5 m³
- Jarak: 50 km
- Layanan: Regular (multiplier = 1)
- Total: (5 × 1.000.000 + 50 × 50.000) × 1 = Rp 7.500.000
```

### Form Request Pindahan

**Kolom Wajib Isi:**
- Nama Lengkap (text, required)
- Nomor Telepon (tel, required)
- Email (email, required)
- Alamat Lengkap (textarea, required)
- Volume Barang (number, required)
- Jarak Tempuh (number, required)
- Jenis Layanan (select, required)

**Kolom Opsional:**
- Catatan Tambahan (textarea)

### Navigasi Section

| Section | ID | Deskripsi |
|---------|----|----|
| Beranda | `#home` | Hero carousel |
| Layanan | `#layanan` | Daftar layanan & statistik |
| Kalkulator | `#kalkulator` | Kalkulator biaya |
| Request | `#pindahan` | Form request pindahan |
| Kontak | `#kontak` | Form kontak & info |

## 🎨 Desain dan Warna

### Color Palette

| Elemen | Warna | Kode |
|--------|-------|------|
| Primary | Biru Modern | `#0066ff` |
| Primary Dark | Biru Gelap | `#0052cc` |
| Secondary | Orange | `#ff7800` |
| Dark Text | Gelap | `#1a1a1a` |
| Light Background | Abu-abu Terang | `#f8f9fa` |
| Border | Abu-abu Terang | `#e0e0e0` |

### Typography

- **Heading Font**: Sora (600-700 weight)
- **Body Font**: Poppins (400-500 weight)
- **Size Scale**: 
  - H1: 3.5rem
  - H2: 2.5rem
  - Body: 1rem

### Responsive Breakpoints

- **Desktop**: ≥ 992px (lg)
- **Tablet**: 768px - 991px (md)
- **Mobile**: < 768px (sm)
- **Extra Small**: < 576px (xs)

## 🔧 Customization

### Mengubah Warna Tema

Edit variabel CSS di file `css/style.css`:

```css
:root {
    --primary-color: #0066ff;        /* Ubah warna primer */
    --secondary-color: #ff7800;      /* Ubah warna sekunder */
    --dark-color: #1a1a1a;           /* Ubah warna gelap */
    /* ... variabel lainnya */
}
```

### Mengubah Harga

Edit formula di file `index.html` dalam function `calculateMovingCost()`:

```javascript
const ratePerM3 = 1000000;      // Harga per m³
const ratePerKm = 50000;        // Harga per km
// Sesuaikan dengan harga Anda
```

### Menambah Section Baru

1. Tambahkan HTML di `index.html`
2. Buat CSS section di `css/style.css`
3. Tambahkan link di navbar jika perlu

## 📱 Fitur Mobile

- ✅ Navbar responsive dengan hamburger menu
- ✅ Carousel touch-friendly
- ✅ Form dengan keyboard optimization
- ✅ Gambar responsive (srcset)
- ✅ Tap-friendly buttons (min 48px)

## 🔐 Keamanan

### Validasi Form
- Client-side validation untuk semua input
- Sanitasi input string
- Format validation untuk email dan telepon

### Best Practices
- HTTPS ready
- Meta tags untuk SEO
- Clean and maintainable code

## 📈 SEO Optimization

- ✅ Semantic HTML5
- ✅ Meta description dan keywords
- ✅ Open Graph tags (siap)
- ✅ Mobile-optimized
- ✅ Fast loading time
- ✅ Proper heading hierarchy

## 🐛 Known Issues & Limitations

1. **Data Persistence**: Saat ini data form disimpan hanya di browser (alert). Untuk production, butuh backend API.
2. **Email Service**: Email konfirmasi belum terintegrasi. Perlu service seperti EmailJS atau Formspree.
3. **Database**: Belum ada database. Perlu integrasi dengan backend untuk menyimpan data pindahan.

## 🎯 Roadmap

- [ ] Integrasi dengan Backend API
- [ ] Sistem autentikasi user
- [ ] Dashboard pelanggan
- [ ] Tracking real-time pindahan
- [ ] Payment gateway (Midtrans/Stripe)
- [ ] Mobile app (React Native/Flutter)
- [ ] Admin dashboard
- [ ] Email notification
- [ ] SMS notification
- [ ] Review dan rating system

## 📝 Lisensi

Project ini tersedia di bawah lisensi MIT. Silakan gunakan dan modifikasi sesuai kebutuhan Anda.

## 👥 Kontribusi

Kami menerima kontribusi dari komunitas! Untuk berkontribusi:

1. Fork repository ini
2. Buat branch feature (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

## 📞 Kontak

**Wuzz - Jasa Pindahan Profesional**

- 📧 Email: cs.wuzz@gmail.com
- 📱 WhatsApp: +62 898 2818 631
- 🕒 Jam Operasional: Senin-Minggu, 07:00-21:00 WIB
- 🌐 Website: https://wuzz.io

## 👨‍💻 Tim Developer

- **UI/UX Design**: Modern & Professional
- **Frontend Development**: HTML, CSS, JavaScript
- **Responsive Design**: Mobile-first approach

## 🙏 Terima Kasih

Terima kasih telah menggunakan Wuzz! Kami berkomitmen memberikan layanan terbaik untuk pindahan Anda.

---

**Last Updated**: April 2024  
**Version**: 2.0 (Redesign Complete)  
**Status**: Active & Maintained ✅
