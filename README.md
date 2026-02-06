# Social Content Manager - Privacy Policy Website

Website sederhana untuk Privacy Policy dan Terms of Service yang diperlukan untuk mendapatkan API access dari TikTok dan Instagram.

## 📁 File Structure

```
privacy-policy-website/
├── index.html      # Halaman utama (Privacy Policy + Terms)
├── styles.css      # Styling
├── callback.html   # OAuth callback handler
└── README.md       # Panduan ini
```

## 🚀 Deploy ke GitHub Pages (GRATIS)

### Langkah 1: Buat GitHub Account (jika belum punya)
1. Buka [github.com](https://github.com)
2. Klik "Sign Up" dan buat account

### Langkah 2: Buat Repository Baru
1. Login ke GitHub
2. Klik tombol "+" di kanan atas → "New repository"
3. Isi form:
   - **Repository name**: `social-content-manager` (atau nama lain)
   - **Description**: Privacy Policy for Social Content Manager
   - Pilih **Public**
   - ✅ Centang "Add a README file"
4. Klik "Create repository"

### Langkah 3: Upload Files
1. Di halaman repository, klik "Add file" → "Upload files"
2. Drag & drop semua file dari folder ini:
   - `index.html`
   - `styles.css`
   - `callback.html`
3. Klik "Commit changes"

### Langkah 4: Aktifkan GitHub Pages
1. Di repository, klik "Settings" (ikon gear)
2. Scroll ke bagian "Pages" di sidebar kiri
3. Di "Source", pilih:
   - Branch: `main`
   - Folder: `/ (root)`
4. Klik "Save"
5. Tunggu 1-2 menit

### Langkah 5: Dapatkan URL
Setelah aktif, URL kamu akan menjadi:
```
https://USERNAME.github.io/social-content-manager/
```

## 🔗 URL untuk API Registration

Gunakan URL berikut saat mendaftar API:

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://USERNAME.github.io/social-content-manager/#privacy` |
| **Terms of Service URL** | `https://USERNAME.github.io/social-content-manager/#terms` |
| **OAuth Redirect URI** | `https://USERNAME.github.io/social-content-manager/callback.html` |

> ⚠️ Ganti `USERNAME` dengan username GitHub kamu!

## ✏️ Kustomisasi

### Ganti Nama App
Edit `index.html` dan ganti "Social Content Manager" dengan nama app kamu.

### Ganti Email Kontak
Di `index.html`, cari `contact@example.com` dan ganti dengan email kamu.

## ✅ Checklist Sebelum Submit API

- [ ] Website sudah live di GitHub Pages
- [ ] Privacy Policy bisa diakses
- [ ] Terms of Service bisa diakses
- [ ] Callback page bisa diakses
- [ ] Sudah test semua link
