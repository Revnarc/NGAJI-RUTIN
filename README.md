🕌 Ngaji Rutin
Ngaji Rutin adalah website dokumentasi momen-momen berkumpul dalam rangka kegiatan ngaji bersama. Website ini menampilkan galeri foto dan video yang tersimpan langsung di Google Drive, serta menyediakan fitur unggah foto dengan sistem keamanan password. Dirancang dengan gaya visual unik perpaduan antara pop punk dan old money, menjadikan tampilannya modern, berani, dan klasik dalam satu nuansa.

🎯 Fitur Utama
Galeri Dinamis
Foto ditampilkan berdasarkan tanggal upload dan dikelompokkan per hari. Tanggal terbaru tampil di bagian atas.

Integrasi Google Drive
Semua media tersimpan langsung di Google Drive. Tidak ada file yang disimpan di server hosting.

Upload Foto dengan Validasi
Pengunjung bisa mengunggah foto melalui modal khusus, dengan pengisian nama file (format tanggal dd/mm/yyyy) dan password untuk validasi.

Batasan Tampilan
Hanya 25 foto terbaru yang ditampilkan untuk menjaga performa. Foto lama tetap tersimpan di Google Drive.

Fitur Inspect Foto
Klik pada foto untuk melihat versi besar dalam modal, lengkap dengan tombol close yang responsif.

Tampilan Elegan & Dinamis

Efek hover dengan zoom dan shadow

Scroll smooth

Tombol “Kembali ke Atas” yang stylish

🧩 Teknologi yang Digunakan
Frontend: HTML5, CSS3, JavaScript (Vanilla)

Desain: Gaya gabungan Pop Punk x Old Money

Storage: Google Drive (melalui Google Apps Script API)

Integrasi Backend: Google Apps Script (untuk handling upload)

🚀 Cara Deploy & Setup
Clone Repo

bash
Copy
Edit
git clone https://github.com/username/ngaji-rutin.git
cd ngaji-rutin
Hosting
Unggah file ke hosting pilihan (Rekomendasi: Netlify, Vercel, atau shared hosting).

Google Drive Setup

Buat folder di Google Drive untuk menyimpan foto.

Gunakan Google Apps Script untuk meng-handle upload file ke Drive dan generate ID/link-nya.

Pastikan Script memiliki izin publik atau hanya bisa diakses dengan password yang sudah diatur.

Konfigurasi

Edit file JavaScript NR 1.js untuk menyesuaikan folder ID Google Drive dan endpoint upload Apps Script.

Edit NR 1.css jika ingin menyesuaikan tema atau tampilan.

📁 Struktur Folder
bash
Copy
Edit
ngaji-rutin/
│
├── index.html
├── NR 1.css              # Styling utama
├── NR 1.js               # JavaScript interaktif
├── assets/               # Ikon, gambar latar, dll
└── README.md
🔒 Keamanan Upload
Password wajib diisi saat mengunggah foto.

Nama file harus mengikuti format tanggal dd/mm/yyyy, jika tidak upload akan ditolak.

Upload hanya bisa dilakukan lewat modal interaktif, bukan melalui Google Drive langsung.

🤝 Kontribusi
Kami terbuka untuk kontribusi dari tim atau komunitas. Silakan fork repo ini dan ajukan pull request untuk fitur atau perbaikan baru.

📸 Preview Tampilan
Tambahkan screenshot website di sini jika diunggah di GitHub.

👨‍💻 Developer
Website ini dikembangkan oleh teman-teman komunitas Ngaji Rutin dengan semangat kebersamaan dan kenangan baik.
Desain dan pengembangan oleh [Developer Utama].
