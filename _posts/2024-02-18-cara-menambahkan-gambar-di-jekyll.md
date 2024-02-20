Untuk menambahkan gambar di situs web yang menggunakan Jekyll, Anda perlu mengikuti beberapa langkah sederhana. Jekyll sendiri adalah generator situs statis yang memungkinkan Anda untuk membuat situs web dengan cepat dan mudah dari file-file sumber, termasuk Markdown dan HTML.

Berikut langkah-langkahnya:

1. Pastikan gambar yang ingin Anda tambahkan sudah tersedia dalam direktori proyek Jekyll Anda.
2. Gunakan Markdown atau HTML untuk menyisipkan gambar di posting atau halaman Jekyll Anda.
Menggunakan Markdown:
markdown
Copy code
![Alt teks](/path/to/image.jpg)
Pastikan untuk mengganti /path/to/image.jpg dengan lokasi relatif gambar dalam struktur proyek Anda.

Menggunakan HTML:
html
Copy code
<img src="/path/to/image.jpg" alt="Alt teks">
Kembali, pastikan untuk mengganti /path/to/image.jpg dengan lokasi relatif gambar dalam struktur proyek Anda.

3. Perbarui situs Anda dengan menjalankan perintah untuk membangun situs Jekyll dan memperbarui server lokal (jika sedang menjalankan server lokal).
Jika Anda menjalankan server lokal untuk pengembangan:

bash
Copy code
bundle exec jekyll serve
Jika tidak, cukup jalankan perintah untuk membangun situs:

bash
Copy code
bundle exec jekyll build
4. Periksa situs Anda di peramban web untuk memastikan gambar ditambahkan dengan benar.
Catatan Tambahan:
Pastikan bahwa gambar tersebut memiliki izin yang sesuai untuk digunakan di situs Anda.
Jika Anda ingin mengatur ukuran gambar atau menambahkan atribut lain seperti class, Anda dapat melakukannya dengan menggunakan HTML langsung.
Selalu pastikan bahwa direktori dan struktur file Anda telah dikonfigurasi dengan benar dalam proyek Jekyll Anda.
Dengan langkah-langkah di atas, Anda akan dapat menambahkan gambar ke situs web Jekyll Anda dengan mudah.





