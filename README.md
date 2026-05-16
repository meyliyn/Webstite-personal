# ⚗️ ChemEdu — Platform Kimia Asam Basa Inovatif

> **Kelompok 8 · S1-Pendidikan Kimia · Universitas Negeri Malang · 2026**

Platform pembelajaran interaktif berbasis web untuk materi **Asam Basa** kelas XI SMA, dilengkapi simulasi pH real-time, animasi partikel, kuis sumatif, dan sistem login/registrasi pengguna.

---

## 🌐 Live Demo

Buka langsung di browser: `index.html` (tidak perlu server, berjalan offline!)

---

## ✨ Fitur Utama

| Fitur | Keterangan |
|-------|-----------|
| 🔐 **Login & Registrasi** | Sistem akun berbasis `localStorage`, dua peran: Guru & Murid |
| 📘 **Materi Lengkap** | Teori Arrhenius, Brønsted-Lowry, Lewis, rumus pH, indikator |
| 🔬 **Simulasi pH Interaktif** | 21 zat kimia, slider konsentrasi, perhitungan real-time |
| 🧬 **Animasi Skala Mikro** | Visualisasi partikel dengan Canvas API |
| 📝 **Ujian Sumatif** | 10 soal pilihan ganda, nilai tersimpan otomatis |
| ✨ **Generate Soal Acak** | Bank soal dinamis dengan umpan balik instan |
| 💬 **Ruang Diskusi** | Chat sederhana antar pengguna |
| 📔 **Refleksi Diri** | Jurnal belajar pribadi yang tersimpan |
| 👨‍🏫 **Panel Guru** | Lihat & hapus nilai murid, edit materi |

---

## 🔐 Sistem Login & Registrasi

### Akun Demo (sudah tersedia)
| Peran | Username | Password |
|-------|----------|----------|
| Guru | `guru_demo` | `guru123` |
| Murid | `murid_demo` | `murid123` |

### Membuat Akun Baru
1. Klik tab **"Daftar"** di halaman login
2. Pilih role: **Murid** atau **Guru**
3. Jika memilih Guru, masukkan **Kode Guru: `CHEM2026`**
4. Isi username (min. 4 karakter, huruf/angka/_), nama lengkap, password (min. 6 karakter)
5. Klik **"Buat Akun"** → otomatis diarahkan ke halaman masuk

> 💡 Semua data akun disimpan di `localStorage` browser. Tidak perlu server/database!

---

## 📂 Struktur Folder

```
chemedu/
├── index.html          ← File utama (semua fitur dalam 1 file)
├── README.md           ← Dokumentasi ini
├── .gitignore          ← File yang diabaikan Git
├── css/                ← (Opsional) CSS terpisah di masa depan
├── js/                 ← (Opsional) JS terpisah di masa depan
└── assets/             ← (Opsional) Gambar & media
```

---

## 🚀 Cara Upload ke GitHub

### Langkah 1 — Buat Repository
1. Buka [github.com](https://github.com) → Login
2. Klik tombol **"New"** (hijau)
3. Isi nama repo: `chemedu-kelompok8`
4. Centang **"Add a README file"** → **Create repository**

### Langkah 2 — Upload File
**Cara A: Upload lewat Web (mudah)**
1. Masuk ke repo → klik **"Add file"** → **"Upload files"**
2. Drag & drop seluruh isi folder `chemedu/`
3. Commit message: `Initial commit - ChemEdu Kelompok 8`
4. Klik **"Commit changes"**

**Cara B: Menggunakan Git (terminal)**
```bash
git init
git add .
git commit -m "Initial commit - ChemEdu Kelompok 8"
git branch -M main
git remote add origin https://github.com/USERNAME/chemedu-kelompok8.git
git push -u origin main
```

### Langkah 3 — Aktifkan GitHub Pages (biar bisa diakses online!)
1. Di repo → klik **Settings** (tab paling kanan)
2. Scroll ke **"Pages"** di sidebar kiri
3. Source: **"Deploy from a branch"**
4. Branch: **main** / folder: **/ (root)**
5. Klik **Save**
6. Tunggu 1-2 menit → URL live muncul: `https://username.github.io/chemedu-kelompok8/`

---

## 🛠️ Teknologi

- **HTML5** — Struktur semantik
- **Tailwind CSS** (CDN) — Styling responsif
- **JavaScript ES6+** — Logika interaktif
- **Canvas API** — Animasi partikel mikro
- **Lucide Icons** — Ikon modern
- **localStorage** — Penyimpanan data lokal

---

## 👥 Tim Pengembang

**Kelompok 8 — S1-Pendidikan Kimia, Universitas Negeri Malang 2026**

---

## 📄 Lisensi

Dibuat untuk keperluan akademik. Bebas digunakan untuk pembelajaran.

---

*⚗️ Belajar Asam Basa Jadi Menyenangkan!*
