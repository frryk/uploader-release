# SF Uploader

<p align="center">
  <img src="https://sportsframe.pages.dev/sportframe.png" alt="SF Uploader Logo" width="90" style="border-radius: 16px;" />
</p>

<p align="center">
  <strong>Otomasi Pengunggahan Foto, Live Tethering Kamera & Auto LUT Tone Grading untuk Fotografer Olahraga</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.3.0-blue?style=flat-square" alt="Version 2.3.0" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-emerald?style=flat-square" alt="Windows and macOS" />
  <img src="https://img.shields.io/badge/Architecture-x64%20%7C%20Apple%20Silicon-purple?style=flat-square" alt="Arch" />
  <img src="https://img.shields.io/badge/License-1--Device%20Lock-amber?style=flat-square" alt="License 1-Device" />
</p>

---

## 📥 Unduh Versi Terbaru (v2.3.0)

Unduh paket rilis resmi sesuai sistem operasi perangkat Anda di tab **[Releases](https://github.com/frryk/uploader-release/releases)**.

| Sistem Operasi | Tipe Paket | Nama Berkas Rilis |
| :--- | :--- | :--- |
| **Windows 64-bit** | Installer Setup | `SF-Uploader-2.3.0-setup.exe` |
| **Windows 64-bit** | Portable (Tanpa Install) | `SF-Uploader-2.3.0-portable.exe` / `.zip` |
| **macOS (Apple Silicon)** | DMG (M1, M2, M3, M4) | `SF Uploader-2.3.0-arm64.dmg` |
| **macOS (Intel)** | DMG (Intel Core i5/i7/i9) | `SF Uploader-2.3.0-x64.dmg` |

---

## ✨ Fitur Unggulan

### 1. ⚡ Direct Wi-Fi FTP Live Tethering & USB Hot Folder
* **Server FTP Lokal Bawaan (Port 2121):** Kamera langsung mengirim file foto ke laptop secara nirkabel saat shutter ditekan.
* **Mendukung Ragam Kamera Utama:** Panduan konfigurasi interaktif 3 kolom untuk **Sony**, **Nikon**, dan **Canon**.
* **Auto-Compress & Auto-Upload:** Foto langsung dikompresi sesuai rasio optimal dan diunggah ke FotoTree event secara *real-time*.

### 2. 🎨 LUT Editor & Auto Tone Grading (Fitur Baru v2.3.0)
* **Impor Preset .XMP & .DNG:** Dukungan impor preset Lightroom kustom untuk diaplikasikan otomatis pada setiap foto yang diunggah.
* **Kontrol Tone Curve Akurat:** Penyesuaian Exposure, Contrast, Highlights, Shadows, Whites, Blacks, Temperature, dan Saturation dengan matematika kurva standar Adobe Lightroom.
* **Preset Lokal Permanen:** Simpan racikan slider kustom ke daftar *Preset Saya* tanpa mengubah preset bawaan standar.
* **Interactive Before/After Split:** Pratinjau split slider responsif 60 FPS dengan orientasi potret dan lanskap otomatis.

### 3. 📁 Batch Folder Upload Cerdas
* Pindai ribuan foto JPG/PNG dari kartu memori atau folder harddisk dalam hitungan detik.
* **Filter Urutan Foto:** Fleksibilitas memilih rentang foto tertentu (contoh: urutan `001 - 300` atau `500 - 800`).
* **Timestamp EXIF Asli:** Pilihan mempertahankan waktu jepret asli dari metadata kamera atau menggunakan waktu unggah.
* **Multi-Thread Upload:** Pengunggahan kelompok foto paralel yang stabil dan minim latensi jaringan.

### 4. 🔍 Integrasi FotoTree & Multi-Akun Kreator
* Cari dan pilih FotoTree event langsung dari aplikasi tanpa perlu membuka browser.
* Manajemen multi-akun kreator dengan perpindahan akun instan.
* Pantau total perolehan daun (*leaves*) dan statistik foto terjual secara transparan.

### 5. 🔒 Lisensi 1-Device Terproteksi
* Sistem verifikasi lisensi terikat identitas unik perangkat (*hardware fingerprint*).
* Mode toleransi offline yang tetap mengizinkan pengunggahan jika koneksi internet event tidak stabil.

---

## 🚀 Panduan Pemasangan (Instalasi)

### 🪟 Untuk Pengguna Windows

#### Opsi 1: Versi Portable (Paling Praktis)
1. Unduh berkas `SF-Uploader-2.3.0-portable.exe` atau berkas `.zip`.
2. Jika mengunduh ZIP, klik kanan &rarr; pilih **Extract All** (Ekstrak Semua).
3. Jalankan aplikasi dengan klik ganda pada `sf-uploader.exe`.
4. *(Opsional)* Buat shortcut ke Desktop: Klik kanan `sf-uploader.exe` &rarr; **Send to** &rarr; **Desktop (create shortcut)**.

#### Opsi 2: Versi Setup Installer
1. Unduh berkas `SF-Uploader-2.3.0-setup.exe`.
2. Jika muncul jendela peringatan *"Windows protected your PC"* (SmartScreen):
   * Klik tulisan **More info** &rarr; klik tombol **Run anyway**.
3. Ikuti wizard instalasi hingga selesai, aplikasi akan otomatis membuat shortcut di Start Menu dan Desktop.

---

### 🍏 Untuk Pengguna macOS

1. Unduh berkas DMG sesuai arsitektur Mac Anda:
   * **Mac M1/M2/M3/M4**: Pilih `SF Uploader-2.3.0-arm64.dmg`.
   * **Mac Intel**: Pilih `SF Uploader-2.3.0-x64.dmg`.
2. Buka berkas `.dmg`, lalu tarik (*drag & drop*) ikon **SF Uploader** ke folder **Applications**.
3. Buka aplikasi dari Launchpad atau folder Applications.

#### Mengatasi Peringatan Gatekeeper ("App is damaged" / "Unidentified Developer")
Karena aplikasi ini didistribusikan secara mandiri tanpa sertifikat berbayar Apple Developer, macOS Gatekeeper mungkin menampilkan peringatan saat pertama kali dibuka.

**Cara mengatasinya sangat mudah:**
1. Buka aplikasi **Terminal** di Mac Anda.
2. Salin dan jalankan perintah berikut, lalu tekan **Enter**:
   ```bash
   xattr -cr /Applications/SF\ Uploader.app
   ```
3. Buka kembali **SF Uploader**. Aplikasi kini akan terbuka normal tanpa kendala.
