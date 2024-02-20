Markdown adalah format penulisan ringan yang dirancang untuk mudah dibaca dan mudah ditulis. Markdown sering digunakan di platform seperti GitHub, Reddit, dan Stack Overflow untuk memformat teks. Berikut adalah beberapa sintaksis dasar Markdown yang umum digunakan:

Header:

shell
Copy code
# Header 1
## Header 2
### Header 3
Hasilnya:

Header 1
Header 2
Header 3
Teks Miring dan Tebal:

markdown
Copy code
*Teks Miring*
**Teks Tebal**
Hasilnya:
Teks Miring
Teks Tebal

Daftar Tandai dan Daftar Bernomor:

markdown
Copy code
- Item 1
- Item 2
  - Subitem A
  - Subitem B

1. Item A
2. Item B
Hasilnya:

Item 1
Item 2
Subitem A

Subitem B

Item A
Item B
Tautan:

less
Copy code
[Teks Tautan](http://www.example.com)
Hasilnya: Teks Tautan

Gambar:

scss
Copy code
![Deskripsi Gambar](URL_gambar)
Gantilah "Deskripsi Gambar" dengan deskripsi yang sesuai dan "URL_gambar" dengan URL gambar.

Blok Kutipan:

markdown
Copy code
> Ini adalah blok kutipan.
Hasilnya:

Ini adalah blok kutipan.

Kode:

go
Copy code
`Kode di dalam satu baris`
atau

go
Copy code
```
Kode lebih dari satu baris
Baris kedua kode
```
Hasilnya:
Kode di dalam satu baris

Kode lebih dari satu baris
Baris kedua kode

Garis Horizontal:

yaml
Copy code
---
Hasilnya:
Tabel:

lua
Copy code
| Judul 1 | Judul 2 |
|---------|---------|
| Data 1  | Data 2  |
Hasilnya:

Judul 1	Judul 2
Data 1	Data 2
Escape Karakter:
Jika Anda ingin menampilkan karakter Markdown sebagai teks biasa, gunakan tanda \ sebelum karakter tersebut.

markdown
Copy code
\*Ini bukan teks miring\*
Hasilnya:
*Ini bukan teks miring*
