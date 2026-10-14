# K3 INSIGHT — Software Engineering Safety & Learning

Website pembelajaran K3 berbasis **HTML, CSS, dan JavaScript murni**. Tidak memakai Laravel, PHP, atau database.

## Fitur
- Beranda modern, responsif, foto, dan navigasi.
- 8 materi dengan halaman detail berbeda dan tombol tandai selesai.
- Pencarian dan filter materi.
- 5 kategori kuis, total 25 soal, serta kuis campuran 10 soal.
- Skor otomatis, pembahasan, riwayat kuis, rata-rata nilai, dan progres materi di browser (`localStorage`).
- CSS dan JavaScript halaman ditanam langsung di HTML; data materi/soal tetap dipisahkan agar mudah diedit.

## Menjalankan lokal
1. Ekstrak ZIP.
2. Buka `index.html` dengan browser atau gunakan Live Server di VS Code.
3. Koneksi internet dibutuhkan untuk foto Unsplash.

## Hosting GitHub Pages
1. Buat repository baru bernama `k3-insight`.
2. Unggah seluruh isi folder `K3-INSIGHT` ke root repository. Pastikan `index.html` berada di root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu tekan **Save**.
6. Setelah proses selesai, situs biasanya bisa diakses melalui `https://USERNAME.github.io/k3-insight/`.

Website statis cocok untuk GitHub Pages. Link aset dan halaman sudah menggunakan path relatif agar dapat bekerja pada URL repository.

## Keamanan
Jangan unggah kata sandi, token, API key rahasia, atau data pribadi ke repository publik.
