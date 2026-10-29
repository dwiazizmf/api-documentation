# GPSTRACKER.IO API Documentation

Dokumentasi OpenAPI / Swagger 2.0 untuk GPSTRACKER.IO API yang telah dikelompokkan (*grouped*) berdasarkan modul fungsional dan tersedia dalam **3 pilihan desain antarmuka**.

---

## 🎨 3 Pilihan Desain Dokumentasi

Cukup **klik dua kali (double-click)** file HTML yang ingin Anda lihat di File Explorer (bisa dibuka langsung di browser tanpa perlu server):

| File | Tampilan | Fitur Unggulan |
|---|---|---|
| **[index.html](file:///c:/Users/dwiaz/Documents/My%20Work/Pekerjaan%20Sekolah/API%20GPSTRCKER%20IO/api-gpstrackerio/index.html)** | **☀️ Modern Light (Scalar)** *(Rekomendasi Utama)* | Desain ultra-modern ala Stripe/Linear dengan tema **Light Mode** cerah & bersih, pencarian cepat (Ctrl+K), multi-language code snippets (cURL, JS, Python, Go, PHP, dll), dan API client interaktif. |
| **[redoc.html](file:///c:/Users/dwiaz/Documents/My%20Work/Pekerjaan%20Sekolah/API%20GPSTRCKER%20IO/api-gpstrackerio/redoc.html)** | **📑 3-Column Enterprise (Redoc)** | Layout 3 kolom standar industri enterprise (Navigasi Kiri - Konten Tengah - Panel Request/Response Gelap di Kanan). Sangat bersih dan mudah dibaca. |
| **[swagger.html](file:///c:/Users/dwiaz/Documents/My%20Work/Pekerjaan%20Sekolah/API%20GPSTRCKER%20IO/api-gpstrackerio/swagger.html)** | **📦 Classic (Swagger UI)** | Desain klasik standar OpenAPI dengan tombol Try-it-out. |

> 💡 **Tip:** Di setiap halaman terdapat menu pill melayang di pojok kanan bawah untuk berpindah antar ketiga desain dengan 1 klik!

---

## 📂 Pembagian Grup Endpoint (Tags)

Total 99 endpoint telah dikelompokkan ke dalam 16 modul:

1. **Authentication & User** (5 endpoint) - Login, ganti password, data user, dan pengaturan akun.
2. **Devices** (8 endpoint) - Registrasi GPS device, manajemen device, dan status aktif.
3. **History & Tracking** (3 endpoint) - Riwayat posisi GPS, koordinat, dan pesan tracking.
4. **Alerts & Alarms** (10 endpoint) - Konfigurasi alert, notifikasi SOS/alarm, dan binding alert ke device.
5. **Events** (8 endpoint) - Riwayat event sistem dan konfigurasi custom event.
6. **Geofences** (4 endpoint) - Pengelolaan zona wilayah virtual (geofence boundary).
7. **Routes** (5 endpoint) - Perencanaan rute dan pelacakan rute perjalanan.
8. **Map Icons & POI** (6 endpoint) - Marker peta kustom dan point of interest.
9. **Reports** (6 endpoint) - Pembuatan dan manajemen laporan analitik aktivitas armada.
10. **Sensors** (5 endpoint) - Sensor kendaraan (ignition, suhu, bahan bakar, dll).
11. **Services & Maintenance** (5 endpoint) - Jadwal servis berkala dan log pemeliharaan armada.
12. **Tasks & Dispatch** (8 endpoint) - Manajemen tugas/surat jalan, status pengiriman, prioritas, dan tanda tangan digital.
13. **Drivers** (6 endpoint) - Profil pengemudi armada kendaraan.
14. **Commands** (5 endpoint) - Pengiriman perintah remote via protokol GPRS dan SMS.
15. **Templates** (14 endpoint) - Template pesan & perintah GPRS dan SMS.
16. **Data Ingestion** (1 endpoint) - Endpoint protokol push data telemetri device (`/insert.php`).

---

## 🛠️ Integrasi Postman & Tools Lainnya
- **Postman**: Klik **Import** -> pilih `oas.json`. Postman akan otomatis membuat folder koleksi per modul.
- **Swagger Editor**: Buka [editor.swagger.io](https://editor.swagger.io/) lalu import `oas.json`.
