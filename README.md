# 🌤️ Weather Check

Aplikasi web modern, ringan, dan responsif untuk mengecek prakiraan cuaca secara instan di berbagai kota di seluruh dunia menggunakan OpenWeatherMap API.

---

## ✨ Fitur Utama

- 🔍 **Pencarian Cuaca Instan**: Cari cuaca kota di seluruh dunia hanya dengan mengetikkan nama kota.
- 🎨 **Dinamika Latar Belakang**: Warna tema latar belakang berubah otomatis menyesuaikan kondisi cuaca (Cerah, Mendung, Hujan, Badai, Salju).
- 📊 **Informasi Komprehensif**: Menampilkan temperatur, sensasi suhu (*feels like*), kelembapan udara, kecepatan angin, dan tekanan atmosfer.
- 🛡️ **Aman & Cepat**: Proteksi sanitasi input terhadap XSS dan penanganan error responsif.
- 📱 **Mobile Friendly**: Tampilan responsif yang nyaman digunakan di berbagai perangkat (desktop, tablet, maupun smartphone).

---

## 🚀 Cara Menjalankan Proyek

1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/bacotbanget1/weather.check.git
   cd weather.check
   ```

2. **Jalankan aplikasi:**
   - Cukup buka file `index.html` langsung di browser favorit Anda (Chrome, Firefox, Safari, Edge).
   - Atau gunakan ekstensi seperti **Live Server** di VS Code.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** & **CSS3** (Flexbox, Grid, CSS Variables, Animations)
- **JavaScript (ES6+)** (Async/Await Fetch API)
- **OpenWeatherMap API**

---

## ⚠️ Catatan Keamanan

Untuk penggunaan di lingkungan *production*, disarankan untuk tidak mengekspos API Key secara publik di sisi klien (frontend). Sebaiknya gunakan *reverse proxy* atau server backend (Node.js/Serverless Function) sebagai perantara pemanggilan API.

---

## 📄 Lisensi

Proyek ini didistribusikan di bawah lisensi [MIT](LICENSE).
