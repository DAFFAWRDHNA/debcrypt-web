# Debcrypt Web

Situs statis untuk membandingkan hash bcrypt dengan kandidat dari wordlist yang ditempel di halaman. `index.html` sudah berada di root repository. Hash dan kandidat diproses di browser dan tidak dikirim ke hosting.

## Aktifkan GitHub Pages

1. Buka [Settings → Pages](https://github.com/DAFFAWRDHNA/debcrypt-web/settings/pages).
2. Pada **Build and deployment → Source**, pilih **GitHub Actions**.
3. Workflow `.github/workflows/pages.yml` akan menerbitkan situs setiap kali ada perubahan di branch `main`.
4. Lihat **Actions** untuk status deployment.

URL situs: https://DAFFAWRDHNA.github.io/debcrypt-web/

