# 📘 Template Laporan Kemajuan Magang MBKM (LaTeX)

Template ini dibuat untuk membantu penyusunan **Laporan Kemajuan Magang MBKM** menggunakan LaTeX secara terstruktur, modular, dan rapi.

Dibuat pada Februari 2026, template ini fokus ke:

- Mempermudah penyusunan laporan
- Struktur modular dan scalable
- Konsisten untuk laporan, logbook, dan sinopsis
- Siap digunakan dengan workflow VS Code + Git

Template sudah disederhanakan sehingga pengguna cukup fokus pada **mengisi konten**, tanpa perlu mengatur struktur dari awal.

---

## ⚙️ Requirement

Sebelum menggunakan template ini, pastikan:

- Compiler menggunakan **XeLaTeX**
- Sudah menginstall distribusi LaTeX (contoh: MiKTeX)
- Menggunakan editor seperti Visual Studio Code (disarankan)

Environment yang digunakan saat pengembangan:

- Visual Studio Code
- MiKTeX
- Extension LaTeX Workshop

Referensi setup lengkap:
Using LaTeX with VS Code and GitHub  
https://medium.com/@erencanbulut/boost-your-latex-workflow-with-vs-code-and-github-f346b74677be

Kenapa saya tidak menggunakan Overleaf?

- Harus terhubung ke internet
- Sering kena limit timeout (berbayar kalau mau extend timeout)
- Compile yang cukup lama dan butuh banyak step tambahan

TAPI template ini juga bisa digunakan di Overleaf dengan cara upload .zip project ini ke Overleaf Projects.

---

## 📂 Struktur Template
├── main.tex
├── logbook.tex
├── sinopsis.tex
│
├── assets/
├── chapters/
├── headers/
├── lists/
├── logbook/
├── template/

---

## 📄 File Utama

### 1. `main.tex`

File utama untuk compile **Laporan Kemajuan**.

### 2. `logbook.tex`

File utama untuk compile **Logbook Magang**.

### 3. `sinopsis.tex`

File utama untuk compile **Sinopsis Magang**.

---

## 📁 Penjelasan Folder

### 📦 `assets/`

Digunakan untuk menyimpan:

- Gambar
- Diagram
- PDF pendukung
- File eksternal lainnya

---

### 📚 `chapters/`

Berisi file per bab:

- bab-1.tex
- bab-2.tex
- bab-3.tex
- dan seterusnya

Struktur ini memudahkan:

- Manajemen dokumen panjang
- Kolaborasi tim
- Version control dengan Git

---

### 📝 `headers/`

Berisi bagian awal laporan seperti:

- Kata Pengantar
- Ringkasan
- Lembar Pengesahan
- Abstrak (jika diperlukan)

---

### 📑 `lists/`

Berisi daftar otomatis seperti:

- Daftar Isi
- Daftar Gambar
- Daftar Tabel
- Daftar Kode
- Daftar Pustaka

---

### 📆 `logbook/`

Berisi file logbook per bulan, misalnya:

- januari.tex
- februari.tex
- maret.tex

---

### 🧩 `template/`

Berisi file reusable untuk beberapa dokumen:

- Cover
- Preamble
- Konfigurasi global

Folder ini memungkinkan:

- Konsistensi format
- Reusability antar `main.tex`, `logbook.tex`, dan `sinopsis.tex`

---

## 🚀 Cara Menggunakan

1. Clone repository ini
2. Buka folder di Visual Studio Code
3. Pastikan compiler diset ke **XeLaTeX**
4. Edit:
   - File di `chapters/` untuk isi laporan
   - File di `headers/` untuk bagian awal
   - File di `logbook/` untuk logbook
5. Compile `main.tex` untuk menghasilkan laporan utama

---

## 🎯 Prinsip Template

Template ini dibuat dengan prinsip:

- Modular
- Clean structure
- Minimal configuration
- Fokus pada konten

Pengguna tidak perlu mengubah struktur atau konfigurasi teknis, cukup mengisi isi laporan sesuai kebutuhan.

# Tambahan

Jika ada bingung cara pakai syntaxnya, silahkan lihat documentation LaTeX / forum LaTeX / StackOverflow atau bahkan ChatGPT/Gemini sejenisnya.

---
