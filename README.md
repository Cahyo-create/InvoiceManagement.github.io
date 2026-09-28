INVOICE EDEN KITCHENS KEMANG - APLIKASI HP (PWA)

ISI FOLDER
  index.html, manifest.webmanifest, sw.js, vendor/, fonts/, icons/, _headers
  Semua library dan font sudah lokal, jadi aplikasi jalan offline.

CARA PASANG DI INTERNET (pilih salah satu, semuanya gratis)
  A. Netlify Drop (paling mudah)
     1. Buka https://app.netlify.com/drop
     2. Ekstrak zip ini, lalu seret FOLDER hasil ekstrak ke halaman itu.
     3. Anda dapat alamat https://nama-acak.netlify.app
  B. GitHub Pages / Cloudflare Pages / Vercel
     Unggah semua isi folder ke repositori, lalu aktifkan Pages.
  PWA wajib memakai HTTPS. Membuka index.html langsung dari HP/laptop
  (alamat file://) tidak bisa diinstal.

CARA INSTAL DI HP
  Android (Chrome): buka alamatnya, ketuk "Pasang" pada banner, atau menu tiga titik > "Instal aplikasi".
  iPhone (Safari): ketuk ikon Bagikan > "Tambahkan ke Layar Utama".

MEMPERBARUI APLIKASI
  Ganti file yang berubah, lalu ubah VERSION di sw.js (mis. 'v1' jadi 'v2')
  supaya HP mengambil versi baru.

PERHATIAN DATA
  Data invoice dan tautan Google Drive tertanam di index.html. Siapa pun
  yang tahu alamat situsnya bisa melihatnya. Untuk situs yang dibagikan
  luas, gunakan pengaturan akses/kata sandi dari layanan hosting.
  Data tambahan yang diketik di aplikasi disimpan di browser masing-masing
  perangkat (tidak tersinkron antar HP).
