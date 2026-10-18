# MazkipGamers 🎮

**PLAY HARD. LEVEL UP.**  
Portal gaming, komunitas, teknologi, dan kreativitas digital oleh Mazkiplay.

## 🌐 Website

- **GitHub Pages:** https://jambudio336-hue.github.io/MazkipGamers/
- **Repository:** https://github.com/jambudio336-hue/MazkipGamers

Website statis menggunakan HTML, CSS, dan JavaScript tanpa framework atau API berbayar. Desain dark premium dengan aksen neon cyan/ungu, animasi ringan, navigasi responsif, dan halaman terpisah yang dapat dibuka langsung melalui URL.

## 🧭 Halaman website

- Beranda — `index.html`
- Dashboard publik — `dashboard.html`
- Fitur — `features.html`
- Pusat unduhan — `downloads.html`
- Tentang MazkipGamers — `about.html`
- Pusat bantuan dan FAQ — `help.html`
- Kebijakan privasi — `privacy.html`
- Syarat penggunaan — `terms.html`
- Lisensi dan atribusi — `license.html`
- Halaman 404 — `404.html`

Dashboard saat ini merupakan pusat navigasi publik, bukan dashboard akun dengan backend. Halaman unduhan menyatakan dengan jelas jika belum ada file resmi yang diterbitkan; tidak ada tombol unduh atau status yang direkayasa.

## 📬 Kontak

- **Email:** [holqinaleavodkabilla@gmail.com](mailto:holqinaleavodkabilla@gmail.com)
- **WhatsApp:** [Chat MazkipGamers](https://wa.me/628562965282)

## 🚀 GitHub Pages dan HTTPS

Workflow `.github/workflows/pages.yml` menerbitkan hanya file website statis ke GitHub Pages agar berkas aplikasi PHP dan sumber lainnya tidak ikut disalin ke artefak situs statis.

1. Buka **Settings → Pages** pada repository.
2. Pada **Build and deployment → Source**, pilih **GitHub Actions**.
3. Pastikan workflow **Deploy MazkipGamers to GitHub Pages** berjalan sukses di tab **Actions**.
4. Buka URL GitHub Pages di atas setelah deployment selesai.
5. Di **Settings → Pages**, aktifkan **Enforce HTTPS** jika opsi tersebut tersedia. Domain `github.io` mendukung HTTPS, tetapi status sertifikat dan publikasi perlu diverifikasi setelah deployment.

Website ini tidak mengumpulkan kata sandi atau pembayaran. Jangan gunakan GitHub Pages untuk transaksi sensitif.

## 🛠️ Pengembangan

Edit file HTML, `style.css`, atau `site.js`, lalu commit ke branch `main`. Workflow akan menerbitkan ulang situs. File PHP yang sudah ada di repo tidak menjadi bagian dari situs statis yang dipublikasikan.

---
© MazkipGamers · Designed with 🎮 by Mazkiplay
