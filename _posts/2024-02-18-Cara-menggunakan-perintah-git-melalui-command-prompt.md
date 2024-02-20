Untuk menggunakan perintah Git melalui Command Prompt (Windows) atau Terminal (Linux/macOS), Anda perlu melakukan beberapa langkah dasar. Berikut adalah beberapa perintah Git umum dan cara penggunaannya:

1. Menginisialisasi Repositori Baru:
bash
Copy code
git init
Perintah ini digunakan untuk membuat repositori Git baru di direktori saat ini.

2. Menambahkan File ke Repositori:
bash
Copy code
git add nama_file
Perintah ini menambahkan file ke staging area, yang merupakan langkah pertama sebelum file tersebut dapat di-commit.

3. Mengecek Status Repositori:
bash
Copy code
git status
Perintah ini menampilkan status perubahan yang belum di-commit di repositori.

4. Membuat Commit:
bash
Copy code
git commit -m "pesan commit"
Perintah ini membuat commit dari perubahan yang sudah di-staging. Pesan commit memberikan deskripsi singkat tentang perubahan yang dilakukan.

5. Melihat Log Commit:
bash
Copy code
git log
Perintah ini menampilkan riwayat commit pada repositori.

6. Membuat Cabang (Branch):
bash
Copy code
git branch nama_cabang
Perintah ini membuat cabang baru dengan nama yang ditentukan.

7. Berpindah ke Cabang Lain:
bash
Copy code
git checkout nama_cabang
Perintah ini memindahkan HEAD ke cabang yang ditentukan.

8. Menggabungkan Cabang:
bash
Copy code
git merge nama_cabang
Perintah ini menggabungkan perubahan dari suatu cabang ke cabang lainnya.

9. Mengunduh Repositori dari GitHub:
bash
Copy code
git clone url_repositori
Perintah ini mengunduh repositori dari GitHub ke komputer lokal.

10. Mengunggah ke Repositori GitHub:
bash
Copy code
git push origin nama_cabang
Perintah ini mengunggah perubahan dari cabang lokal ke repositori di GitHub.

11. Mengambil Perubahan dari Repositori GitHub:
bash
Copy code
git pull origin nama_cabang
Perintah ini mengambil perubahan terbaru dari repositori di GitHub ke cabang lokal.

Catatan:
Pastikan Anda berada di direktori repositori yang benar sebelum menggunakan perintah Git.
Gantilah "nama_file", "nama_cabang", dan "url_repositori" dengan nilai yang sesuai dengan proyek Anda.
