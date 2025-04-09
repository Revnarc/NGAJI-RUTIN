# 📸 Ngaji Rutin — Dokumentasi Momen, Simpan Cerita

**Ngaji Rutin** adalah website custom yang dikembangkan untuk mendokumentasikan momen-momen pertemanan secara otomatis dan efisien. Dibangun dari nol tanpa CMS, website ini fokus pada galeri foto berbasis waktu yang langsung terintegrasi dengan **Google Drive** melalui **Google Apps Script**, memungkinkan upload dan display foto tanpa perlu backend konvensional.

---

## 🛠️ Dibalik Layar: Cara Kerja Website

Website ini dibangun dengan stack ringan namun fungsional:

### 🧩 Frontend:
- **HTML + Tailwind CSS**: Struktur bersih dan desain responsif
- **Vanilla JavaScript**: Untuk interaksi dinamis (modal, validasi, scroll)
- **Custom UI Upload**: Form upload foto + input tanggal & password

### ☁️ Backend & Storage:
- **Google Apps Script**: Menangani proses upload langsung ke Google Drive, rename file otomatis, dan validasi data
- **Google Drive API**: Digunakan sebagai penyimpanan cloud dan sumber foto untuk galeri
- **Spreadsheet Logging** *(opsional)*: Untuk mencatat metadata file yang diunggah (jika diperlukan monitoring)

---

## 🔍 Fitur Utama

- ✅ **Upload Otomatis ke Google Drive**  
  File yang diunggah lewat form langsung masuk ke folder Drive yang ditentukan tanpa user melihat antarmuka Drive.

- ✅ **Validasi Nama File**  
  User wajib mengganti nama file sesuai format `dd-mm-yyyy`. Upload diblok jika format salah.

- ✅ **Minimal 3 Orang dalam Foto**  
  Ini aturan internal. Upload valid hanya jika foto memuat minimal 3 anggota—ditampilkan sebagai peringatan di UI.

- ✅ **Galeri Dinamis**  
  Galeri menampilkan **25 foto terbaru**, dikelompokkan per tanggal upload. Foto lama tetap tersimpan di Drive.

- ✅ **Inspect Photo Modal**  
  Klik foto untuk melihat preview ukuran besar, lengkap dengan tombol close elegan.

- ✅ **Smooth UX**  
  - Scroll-to-top button  
  - Hover effect pada galeri  
  - Galeri dibatasi `max-height` agar tetap fokus ke cerita di bawah

---

## 📆 Timeline Proyek

- 💡 Ide awal muncul: **27 Agustus 2024**
- 📐 Riset dan perancangan UI/UX: September–Oktober 2024
- 💤 Sempat tidak dilanjutkan beberapa bulan
- 🚀 Launching dan live: **10 April 2025**

---

## 👨‍💻 Developer Notes

Proyek ini dikembangkan sebagai dokumentasi internal, namun dibangun dengan standar layaknya aplikasi web publik. Tujuannya adalah:

- Menerapkan **serverless architecture** via Google Apps Script
- Mengeksplorasi integrasi seamless antara frontend custom dengan Google Drive
- Menjaga struktur file tetap sederhana, mudah dirawat dan diekspansi

> Web ini tidak bergantung pada database eksternal, namun sepenuhnya berjalan di atas ekosistem Google—membuatnya ringan, murah, dan fleksibel.

---

## 📌 Catatan Akhir

Ngaji Rutin adalah proyek yang lahir dari kebutuhan nyata: menyimpan momen dengan cara yang efisien dan menyenangkan. Dibangun dengan hati oleh satu developer, untuk satu geng yang gak akan pernah tergantikan.

> _"Karena bukan cuma fotonya yang disimpan, tapi semua cerita di baliknya."_
