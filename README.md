# Program Kerja KKN UNISA Yogyakarta 2025

Dokumentasi statis KKN untuk publikasi via **GitHub Pages** atau **Netlify**.

## Struktur Folder
```
kkn-blog/
├─ index.html
├─ 404.html
├─ assets/
│  ├─ css/style.css
│  ├─ js/main.js
│  └─ img/ (taruh foto di sini)
└─ pages/
   ├─ proker1.html ... proker17.html
```

## Cara Jalankan Lokal (Laragon)
1. Salin folder `kkn10-blog` ke `C:\laragon\www\kkn-blog`
2. Jalankan Laragon → Apache (Start).
3. Akses: `http://localhost/kkn-blog/` atau jika pakai Virtual Host Laragon: `http://kkn-blog.test/`

## Publish ke GitHub Pages (cara cepat)
1. Buat repository **public** bernama `kkn10-blog` di GitHub.
2. Upload semua file/folder di atas (bisa lewat VS Code atau web GitHub).
3. Buka tab **Settings → Pages** → Source: `Deploy from branch`, Branch: `main`.
4. Tunggu 1—2 menit, lalu akses: `https://username.github.io/kkn10-blog/`

## Publish ke Netlify (drag & drop)
1. Login Netlify → **Add new site → Deploy manually**.
2. Drag-drop folder `kkn10-blog` (pastikan `index.html` ada di root).
3. Selesai! Alamatnya akan seperti `https://namasitus.netlify.app`.

> Semua tautan dibuat **relatif**, jadi aman untuk subfolder di GitHub Pages maupun Netlify.
=======
# kkn10-blog
