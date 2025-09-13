# CustomVSCODE

Selamat datang di **CustomVSCODE**! Proyek ini bertujuan untuk memberikan pengalaman Visual Studio Code yang lebih personal, estetis, dan fungsional melalui kustomisasi tampilan dan fitur.

## ✨ Fitur Utama

- **Kustomisasi Tampilan**: Menggunakan file CSS untuk mengubah warna, font, dan elemen UI lainnya agar lebih menarik.
- **Fitur Interaktif**: Menambahkan skrip JavaScript untuk meningkatkan produktivitas dan memberikan pengalaman pengguna yang lebih baik.
- **Ilustrasi Visual**: Menyediakan elemen grafis untuk mempercantik antarmuka editor.
- **Pengaturan yang Mudah**: File `settings.json` yang telah dikonfigurasi untuk mempermudah aktivasi kustomisasi.

## 📂 Struktur Proyek

- `BKW.css`: File CSS yang berisi aturan gaya untuk mengubah tampilan Visual Studio Code.
- `BKW.js`: File JavaScript untuk menambahkan fitur interaktif.
- `illustration.svg`: File ilustrasi yang dapat digunakan untuk elemen visual tambahan.
- `settings.json`: File pengaturan Visual Studio Code yang telah dikustomisasi.

## 🚀 Panduan Penggunaan

Ikuti langkah-langkah berikut untuk mengaktifkan kustomisasi ini:

### 1. Persiapan

- Pastikan Anda telah menginstal Visual Studio Code di komputer Anda.
- Unduh atau klon repositori ini ke direktori lokal Anda:
  ```bash
  git clone https://github.com/bolopakw01/CustomVSCODE.git
  ```

### 2. Aktifkan Kustomisasi

1. Buka file `settings.json` yang ada di folder proyek ini.
2. Cari bagian berikut:
   ```json
   // "vscode_custom_css.imports": [
   //     "file:///D:/CODE/CustomVSCODE/BKW.css",
   //     "file:///D:/CODE/CustomVSCODE/BKW.js"
   // ]
   ```
3. Hapus komentar (`//`) di depan baris tersebut sehingga menjadi:
   ```json
   "vscode_custom_css.imports": [
       "file:///D:/CODE/CustomVSCODE/BKW.css",
       "file:///D:/CODE/CustomVSCODE/BKW.js"
   ]
   ```

### 3. Restart Visual Studio Code

- Tutup dan buka kembali Visual Studio Code untuk menerapkan perubahan.
- Jika Anda menggunakan ekstensi "Custom CSS and JS Loader", pastikan ekstensi tersebut aktif.

### 4. Verifikasi

- Setelah restart, periksa apakah tampilan dan fitur baru telah diterapkan.
- Jika tidak ada perubahan, pastikan jalur file di `settings.json` sesuai dengan lokasi file di komputer Anda.

## ⚠️ Catatan Penting

- **Error "Installation Corrupt"**: Jika Anda mengalami error ini, nonaktifkan sementara kustomisasi dengan menambahkan kembali komentar (`//`) pada pengaturan di `settings.json`.
- **Kompatibilitas**: Pastikan Anda menggunakan versi Visual Studio Code yang mendukung ekstensi "Custom CSS and JS Loader".
- **Backup**: Sebelum mengubah pengaturan, disarankan untuk membuat salinan cadangan file `settings.json` Anda.

## 💡 Tips Kustomisasi

- Anda dapat mengedit file `BKW.css` untuk menyesuaikan warna, font, dan elemen UI lainnya sesuai preferensi Anda.
- Gunakan file `BKW.js` untuk menambahkan skrip JavaScript yang dapat meningkatkan produktivitas, seperti pintasan keyboard atau fitur otomatisasi.
- Tambahkan ilustrasi atau elemen visual lainnya ke dalam proyek untuk menciptakan pengalaman coding yang lebih menyenangkan.

## 📜 Lisensi

Proyek ini dilisensikan di bawah lisensi MIT. Anda bebas untuk menggunakan, memodifikasi, dan mendistribusikan proyek ini dengan tetap mematuhi ketentuan lisensi.

---

💻 **Dibuat dengan cinta oleh [bolopakw01](https://github.com/bolopakw01)**. Jangan ragu untuk memberikan saran atau melaporkan masalah melalui halaman [Issues](https://github.com/bolopakw01/CustomVSCODE/issues).