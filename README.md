# Debcrypt Web

Situs statis untuk membandingkan hash bcrypt dengan kandidat dari wordlist yang ditempel di halaman. `index.html` sudah berada di root repository. Hash dan kandidat diproses di browser dan tidak dikirim ke hosting.

## Aktifkan situs

Buka [Settings → Pages](https://github.com/DAFFAWRDHNA/debcrypt-web/settings/pages), lalu pada **Build and deployment** pilih:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/(root)`

Klik **Save**. Setelah GitHub Pages selesai menerbitkan, situs dapat dibuka di:

https://DAFFAWRDHNA.github.io/debcrypt-web/

GitHub Pages menerbitkan isi branch/folder yang dipilih; untuk situs ini, halaman masuk `index.html` berada di root branch `main`.

