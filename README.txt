IKY — DIGITAL PORTFOLIO
=======================

ISI FOLDER
- index.html
- iky-photo.jpg
- school-logo.jpg

CARA MENJALANKAN LOKAL
1. Ekstrak ZIP.
2. Pastikan index.html dan folder assets berada sejajar di folder yang sama.
3. Buka index.html di browser.

PUBLIKASI KE GITHUB PAGES
1. Buka repository GitHub yang dipakai untuk website.
2. Upload SEMUA isi folder ini, bukan hanya index.html.
3. Pastikan struktur repository tepat seperti ini:
   index.html
   iky-photo.jpg
   school-logo.jpg
4. Perhatikan huruf besar/kecil nama folder dan file. GitHub Pages berjalan di server Linux yang case-sensitive.
5. Buka Settings > Pages, pastikan source dan branch yang dipilih benar (misalnya Deploy from a branch, branch main, folder /(root)).
6. Setelah upload, tunggu deployment selesai di tab Actions / Pages, lalu refresh website. Coba hard refresh atau buka lewat mode samaran jika masih melihat versi cache.

PEMANGGILAN FOTO DI HTML
- Foto profil: .iky-photo.jpg
- Logo sekolah: .school-logo.jpg
Nama file harus sama persis, termasuk ekstensi .jpg. Jangan mengganti nama hanya di GitHub atau hanya di HTML.

JIKA FOTO MASIH TIDAK MUNCUL
- Buka URL foto secara langsung dengan menambahkan /assets/iky-photo.jpg pada alamat website. Contoh: https://USERNAME.github.io/NAMA-REPO/assets/iky-photo.jpg (untuk project site). Untuk user site, biasanya https://USERNAME.github.io/assets/iky-photo.jpg.
- Jika URL menampilkan 404, berarti file tidak berada pada lokasi yang diharapkan atau nama/path berbeda.
- Pastikan folder bernama assets (huruf kecil), bukan Assets, dan file bukan tersimpan di assets/assets/.
- Pastikan yang diunggah adalah file JPG asli, bukan shortcut atau file dengan ekstensi ganda seperti .jpg.jpg.

Catatan: tema website telah diubah menjadi tema profesional bernuansa alam dengan latar solid, panel terang, dan aksen hijau. Kartu identitas tetap mempertahankan desain cetaknya.
