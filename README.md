# ⚡ Sportsframe Auto Uploader

<p align="center">
  <img src="https://sportsframe.pages.dev/assets/logo.png" alt="Sportsframe Logo" width="90" style="border-radius: 16px;" />
</p>

<p align="center">
  <strong>Solusi Pengunggahan Foto Otomatis & Live Tethering Kamera untuk Fotografer Olahraga</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0.0-blue?style=flat-square" alt="Version 2.0.0" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-emerald?style=flat-square" alt="Windows and macOS" />
  <img src="https://img.shields.io/badge/License-Sportsframe%20Official-amber?style=flat-square" alt="Official License" />
  <img src="https://img.shields.io/badge/Architecture-x64%20%7C%20Apple%20Silicon-purple?style=flat-square" alt="Arch" />
</p>

---

## 📥 Unduh Versi Terbaru (v2.0.0)

Pilih installer sesuai sistem operasi Anda di tab **[Releases](https://github.com/USERNAME/REPO_NAME/releases/latest)**:

| Sistem Operasi | Format | Status | Keterangan |
| :--- | :--- | :--- | :--- |
| **Windows 10 / 11 (64-bit)** | 📦 [**Portable (.zip)**](https://github.com/USERNAME/REPO_NAME/releases/latest) | ⭐ **Sangat Direkomendasikan** | *Ekstrak langsung pakai, bebas instalasi & tanpa izin admin.* |
| **Windows 10 / 11 (64-bit)** | 💿 [**Setup (.exe)**](https://github.com/USERNAME/REPO_NAME/releases/latest) | Standar Installer | *Installer wizard dengan shortcut Desktop.* |
| **macOS (Intel / Apple Silicon)** | 🍏 [**Installer (.dmg)**](https://github.com/USERNAME/REPO_NAME/releases/latest) | macOS Universal | *Drag-and-drop ke folder Applications.* |

---

## ✨ Fitur Unggulan

### 1. ⚡ Direct Wi-Fi FTP Live Tethering (Tanpa Kabel & Tanpa Software Tambahan)
* **Server FTP Bawaan (Port 2121):** Kamera langsung mengirim foto ke laptop secara nirkabel setiap kali shutter ditekan.
* **Auto-Compress & Auto-Upload:** Foto otomatis dioptimasi sesuai standar FotoYu dan langsung masuk ke FotoTree event Anda secara *real-time*.

### 2. 📁 Batch Folder Upload
* Pindai ribuan foto JPG/PNG dari folder lokal atau memory card.
* **Filter Urutan File:** Pilih rentang foto tertentu (contoh: urutan `001 - 300` atau `500 - 800`).
* **Timestamp Fleksibel:** Gunakan tanggal/jam asli dari metadata **EXIF kamera** atau jam saat diunggah.
* **Batching Efisien:** Upload stabil dalam kelompok 20 foto secara simultan.

### 3. 🔍 Pencarian & Integrasi FotoTree Terpadu
* Cari dan pilih FotoTree langsung dari aplikasi tanpa perlu membuka browser.
* Pantau total perolehan *leaves* dan statistik kreator Anda secara langsung.

### 4. 🔒 Keamanan & Lisensi 1-Device
* Sistem aktivasi terikat identitas unik perangkat untuk stabilitas akun.

---

## 🚀 Panduan Pemasangan (Instalasi)

### 🪟 Untuk Pengguna Windows

#### Opsi 1: Versi ZIP Portable (Paling Mudah)
1. Unduh file `Sportsframe-Auto-Uploader-2.0.0-win.zip`.
2. Klik kanan file ZIP &rarr; pilih **Extract All** (Ekstrak Semua).
3. Buka folder hasil ekstrak, lalu klik ganda pada `fotoyu-uploader.exe`.
4. *(Opsional)* Buat shortcut ke Desktop: Klik kanan `fotoyu-uploader.exe` &rarr; **Send to** &rarr; **Desktop (create shortcut)**.

#### Opsi 2: Versi Setup Installer (.exe)
1. Unduh file `Sportsframe-Auto-Uploader-2.0.0-setup.exe`.
2. Jika muncul peringatan *"Windows protected your PC"* (SmartScreen):
   * Klik tulisan **More info** &rarr; lalu klik tombol **Run anyway**.
3. Ikuti langkah pada wizard instalasi hingga selesai.

---

### 🍏 Untuk Pengguna macOS

1. Unduh file `Sportsframe-Auto-Uploader-2.0.0.dmg`.
2. Buka file `.dmg`, lalu tarik (*drag*) icon **Sportsframe** ke folder **Applications**.
3. **Jika muncul peringatan Gatekeeper ("App is damaged" atau "Unidentified Developer"):**
   Buka aplikasi **Terminal** di Mac Anda, lalu ketik perintah berikut:
   ```bash
   xattr -cr /Applications/Sportsframe\ Auto\ Uploader.app
