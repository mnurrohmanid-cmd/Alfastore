# CIBILI - Vercel PHP

Struktur:
- api/index.php
- api/proxy.php
- vercel.json

Keduanya tetap PHP karena aplikasi asli menggunakan PHP dan encrypted application loader.
Jangan ubah menjadi index.html/proxy.js karena browser akan menampilkan source PHP sebagai teks.

Deploy:
1. Upload seluruh isi folder ini ke repository GitHub.
2. Import repository tersebut ke Vercel.
3. Vercel akan menjalankan PHP melalui runtime vercel-php@0.9.0.
