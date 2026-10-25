# TaniFriends 🌱

Website prototype berbahasa Indonesia untuk edukasi pertanian, informasi komoditas, kalender tanam, dan catatan usaha tani.

## Fitur
- Beranda responsif dengan ringkasan harga komoditas demo.
- Halaman komoditas, profil budidaya, standar kualitas ringkas, dan favorit.
- Pojok edukasi dengan artikel yang dapat dibaca.
- Kalender tanam/panen contoh.
- Simulasi login profil tanpa kata sandi.
- Catatan hasil panen, pendapatan, dan biaya produksi tersimpan di browser (`localStorage`).
- Ekspor catatan ke CSV.
- Layout responsif untuk desktop dan HP.

## Penting sebelum dipakai
- Harga komoditas adalah **data ilustrasi**, bukan data real-time atau data resmi.
- Sentra produksi dan informasi budidaya adalah ringkasan contoh yang harus divalidasi untuk penggunaan operasional.
- Login bukan autentikasi sungguhan; tidak ada server/database.
- Catatan hanya tersimpan di browser/perangkat yang digunakan.

## Cara menjalankan lokal
1. Ekstrak ZIP.
2. Buka `index.html` di browser. Untuk pengalaman paling konsisten, jalankan melalui server lokal seperti VS Code Live Server.

## Cara publikasi gratis dengan GitHub Pages
1. Masuk ke https://github.com dan buat repository baru bernama `tanifriends` (Public).
2. Unggah `index.html`, `styles.css`, `app.js`, dan `README.md` dari folder ini ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses deployment selesai. GitHub akan menampilkan URL website pada halaman Pages, biasanya berformat `https://USERNAME.github.io/tanifriends/`.
7. Buka URL tersebut dan tes fitur, lalu bagikan URL itu.

## Cara publikasi dengan Vercel
1. Unggah folder project ini ke repository GitHub.
2. Masuk ke https://vercel.com dan pilih **Add New → Project**.
3. Import repository `tanifriends`.
4. Karena ini website statis tanpa build step, biarkan Framework Preset sebagai **Other** dan Build Command kosong.
5. Klik **Deploy**. Setelah berhasil, Vercel memberikan URL `.vercel.app` yang dapat dibagikan.

## Kustomisasi
- Ubah daftar komoditas, contoh harga, dan artikel di `app.js`.
- Ubah warna dan tata letak di `styles.css`.
- Ubah judul, metadata, dan struktur halaman di `index.html`.

## Lisensi
Prototype pendidikan; silakan modifikasi sesuai kebutuhan.
