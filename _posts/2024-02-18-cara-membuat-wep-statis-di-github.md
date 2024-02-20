Untuk membuat situs web statis di GitHub, Anda dapat menggunakan GitHub Pages. Berikut langkah-langkahnya:

Buat Repositori di GitHub:

Buka GitHub dan masuk ke akun Anda.
Klik tombol "+" di pojok kanan atas dan pilih "New repository".
Beri nama repositori sesuai dengan nama situs web Anda.
Pilih opsi untuk membuat README file jika Anda ingin, dan tekan "Create repository".
Buat Struktur Dasar Proyek:

Setelah membuat repositori, Anda perlu menambahkan file-filenya.
Tambahkan file index.html ke repositori sebagai halaman utama situs web Anda. Anda juga dapat menambahkan file CSS, JavaScript, dan aset lainnya sesuai kebutuhan.
Commit Perubahan:

Setelah menambahkan file, lakukan commit ke repositori.
Buka terminal atau command prompt di komputer Anda.
Pindah ke direktori proyek Anda menggunakan perintah cd.
Inisialisasi Git di direktori proyek Anda dengan perintah git init.
Tambahkan file ke Git dengan perintah git add ..
Lakukan commit dengan perintah git commit -m "Initial commit".
Pindahkan ke Branch gh-pages:

Buat branch baru dengan nama gh-pages. Branch ini secara otomatis di-host oleh GitHub sebagai GitHub Pages.
Gunakan perintah berikut di terminal:
bash
Copy code
git checkout -b gh-pages
Push ke GitHub:

Dorong branch gh-pages ke GitHub dengan perintah:
bash
Copy code
git push origin gh-pages
Aktifkan GitHub Pages:

Buka repositori di GitHub.
Pergi ke tab "Settings".
Gulir ke bawah ke bagian "GitHub Pages".
Pilih branch gh-pages sebagai branch sumber.
Tekan "Save".
Akses Situs Web:

GitHub Pages akan membangun situs web dan memberikan URL tempat situs web Anda dapat diakses. URL ini biasanya memiliki format https://username.github.io/namarepositori.
Sekarang, situs web statis Anda telah berhasil di-host di GitHub Pages. Anda dapat terus memperbarui repositori dan GitHub Pages akan secara otomatis memperbarui situs web. Pastikan untuk memeriksa dokumentasi resmi GitHub Pages untuk informasi lebih lanjut: https://docs.github.com/en/pages.





