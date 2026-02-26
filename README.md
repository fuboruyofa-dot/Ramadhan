# 🌙 Ramadan Growth Tracker

Aplikasi habit tracker personal untuk Ramadan 1446H — dirancang untuk membantu kamu lebih produktif secara spiritual, fisik, dan karier selama bulan Ramadan.

## ✨ Fitur

- 🕌 **Ibadah** — Al-Quran, Fajr, Qiyamul Lail, Dhikr, Tarawih
- 💪 **Health** — Exercise sebelum Iftar, Hydration, Sleep, Suhoor
- 💻 **Career** — Embedded Systems, Coding, English, LinkedIn
- 🧠 **Mind** — Reading, Gratitude Journal, No Social Media
- 📅 Navigasi 30 hari Ramadan
- 📊 Progress bar & completion rate per kategori
- 🔥 30-day streak tracker
- ✍️ Daily reflection notes
- 💾 Auto-save ke localStorage

---

## 🚀 Deploy ke Vercel via GitHub

### Langkah 1 — Buat Repository GitHub

```bash
# Inisialisasi git di folder project
git init
git add .
git commit -m "🌙 Initial commit: Ramadan Growth Tracker"
```

Kemudian buat repo baru di [github.com/new](https://github.com/new):
- Repository name: `ramadan-growth-tracker`
- Visibility: Public (gratis di Vercel)
- Jangan centang "Add README"

Lalu push:
```bash
git remote add origin https://github.com/USERNAME/ramadan-growth-tracker.git
git branch -M main
git push -u origin main
```

> Ganti `USERNAME` dengan username GitHub kamu.

---

### Langkah 2 — Deploy ke Vercel

1. Buka [vercel.com](https://vercel.com) dan login/daftar (bisa pakai akun GitHub)
2. Klik **"Add New Project"**
3. Klik **"Import Git Repository"**
4. Pilih repo `ramadan-growth-tracker`
5. Di bagian **Configure Project**:
   - Framework Preset: **Other**
   - Root Directory: `./` (default)
   - Build Command: *(kosongkan)*
   - Output Directory: *(kosongkan)*
6. Klik **Deploy** 🚀

Tunggu ~30 detik, aplikasi kamu live di URL seperti:
`https://ramadan-growth-tracker.vercel.app`

---

### Langkah 3 — Update Otomatis

Setiap kali kamu push ke GitHub, Vercel otomatis redeploy:

```bash
# Edit file, lalu:
git add .
git commit -m "update: deskripsi perubahan"
git push
```

---

## 📁 Struktur Project

```
ramadan-growth-tracker/
├── index.html        # Aplikasi utama (single file)
├── vercel.json       # Konfigurasi Vercel
├── package.json      # Project metadata
├── .gitignore        # File yang diabaikan git
└── README.md         # Dokumentasi ini
```

---

## 🛠️ Jalankan Secara Lokal

Cukup buka `index.html` di browser, atau:

```bash
npx serve .
# Buka http://localhost:3000
```

---

## 🤲 Ramadan Kareem

Semoga Ramadan ini penuh berkah, produktivitas, dan pertumbuhan pribadi. Istiqomah!
