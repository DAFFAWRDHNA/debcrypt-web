# Debcrypt Web

Situs statis untuk membandingkan hash bcrypt dengan kandidat dari wordlist yang ditempel di halaman. Berkas `index.html` sudah memuat seluruh dependensi; tidak perlu backend. Hash dan daftar kandidat diproses di browser, tidak dikirim ke hosting.

## Publikasikan dengan GitHub Pages

1. Buat repository GitHub baru dan pilih **Public** agar situs dapat dibuka online.
2. Unggah `index.html` dari folder ini ke root repository.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu simpan.
5. Tunggu hingga GitHub Pages menampilkan URL situs di halaman Settings → Pages.

`start-debcrypt.py` dan `start-debcrypt.bat` hanya dipakai untuk menjalankan server lokal; keduanya tidak diperlukan di hosting.

