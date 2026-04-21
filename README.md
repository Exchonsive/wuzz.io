# 🚚 Wuzz - Jasa Pindahan Profesional
Wuzz adalah platform digital untuk layanan pindahan rumah dan kantor yang modern, aman, dan terpercaya. Kami menyediakan solusi pindahan yang mudah dan efisien dengan harga transparan.

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
- **HTML5**
- **CSS3**
- **Bootstrap 5.3.2**
- **JavaScript Vanilla**

### Libraries & Tools
- **AOS (Animate On Scroll)**
- **Google Fonts**
- **Icofont**
- **Responsive Design**

## 🚀 Cara Menggunakan

### Persyaratan
- Browser modern dengan JavaScript enabled
- Koneksi internet stabil
- Resolusi minimal 320px (mobile)

### Instalasi Lokal

1. **Clone repository**
   ```bash
   git clone https://github.com/Exchonsive/wuzz.io.git
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

---

**Last Updated**: April 2024  
**Version**: 2.0 (Redesign Complete)  
**Status**: Active & Maintained ✅
