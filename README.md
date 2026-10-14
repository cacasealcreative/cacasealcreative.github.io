# Portofolio Syahrul Adi Mustofa — Pink Theme

Website portofolio statis yang siap dipublikasikan menggunakan **GitHub Pages**. Tidak memerlukan framework, build tools, atau backend.

## File
- `index.html` — struktur dan konten website.
- `style.css` — desain pink, layout responsif, dan tampilan mobile.
- `script.js` — menu mobile, navigasi aktif, dan tombol kembali ke atas.
- `.nojekyll` — membantu GitHub Pages menyajikan file statis tanpa pemrosesan Jekyll.

## Cara publish di GitHub Pages
1. Buat repository baru di GitHub. Untuk situs utama akun, namai repository `USERNAME.github.io` (ganti `USERNAME` dengan username GitHub kamu). Atau gunakan repository biasa untuk project site.
2. Upload **isi folder ini** ke root repository: `index.html`, `style.css`, `script.js`, `.nojekyll`, dan `README.md`.
3. Buka **Settings → Pages** pada repository.
4. Di bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses deployment selesai. URL situs akan ditampilkan pada halaman Settings → Pages.

## Sebelum dipublikasikan
- Periksa dan sesuaikan nama, ringkasan profil, pengalaman, email, lokasi, sertifikasi, dan pencapaian agar datanya akurat.
- Ganti kartu proyek contoh pada bagian `#projects` dengan proyek asli. Tautan GitHub pada kartu masih berupa tautan umum.
- Ganti `https://github.com/` dengan URL profil GitHub kamu.
- Email kontak menggunakan `mailto:` sehingga membuka aplikasi email pengunjung; tidak memerlukan backend.
- Font Google Fonts memerlukan internet. Jika tidak tersedia, website menggunakan font sistem sebagai fallback.

## Menyesuaikan warna
Edit variabel CSS di awal `style.css`: `--pink`, `--pink2`, `--pink-pale`, dan `--plum`.
