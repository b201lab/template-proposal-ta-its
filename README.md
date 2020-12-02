# Template Proposal Tugas Akhir ITS (Institut Teknologi Sepuluh Nopember) Berbasis LaTeX

Repositori ini berisi _template_ dari proposal tugas akhir berbasis [**LaTeX**](https://www.latex-project.org/) yang disesuaikan dengan format yang diberlakukan oleh [**Institut Teknologi Sepuluh Nopember**](https://www.its.ac.id/).
_Template_ yang dibuat saat ini baru mengikuti aturan yang diberlakukan oleh **Departemen Teknik Komputer** **FTEIC** - **ITS** dengan sedikit penyesuaian, sehingga, secara penuh _template_ ini belum mewakili aturan yang berlaku secara umum di setiap departemen yang ada di **ITS**.
Untuk itu, diharapkan adanya kontribusi dari pihak yang bersedia membantu agar nantinya _template_ ini bisa konsisten digunakan setiap tahun dengan menyesuaikan aturan dari setiap departemen yang ada di **ITS**.

> Perlu diketahui, _template_ ini bukanlah _template_ resmi yang dikeluarkan oleh **ITS** maupun departemen-departemen yang ada di bawah naungan **ITS**.

## Fitur

- Format ukuran halaman, _margin_, dan _font_ yang disesuaikan dengan aturan yang berlaku di **ITS**.
- Disertai bagian-bagian yang umumnya diperlukan seperti pengesahan, latar belakang, tinjauan pustaka, dsb.
- Pembuatan daftar pustaka secara otomatis.
- Penomoran gambar dan referensi secara otomatis.
- _Input_ gambar dengan format **JPEG**, **PNG**, maupun format lain.
- Pembuatan daftar, persamaan, dan tabel.

## Cara Menggunakan Template

Bagian utama dokumen terletak pada _file_ `main.tex` yang digunakan untuk mengatur _package_ apa saja yang digunakan serta _file_ lain yang akan di-_inputkan_.
Setelah dilakukan kompilasi, hasilnya akan ada banyak _file_ `main` dengan format yang berbeda.
Yang terpenting adalah _file_ `main.pdf` yang merupakan hasil akhir dari kompilasi dokumen tersebut.

Selain itu ada beberapa bagian lain dari _template_ ini selain `main.tex` yang bisa diubah, seperti:
- **_Folder_ `konten`**, berisi _file_ `*.tex` dari bagian-bagian yang akan dimasukkan pada proposal tugas akhir.
- **_Folder_ `pengesahan`**, berisi _file_ `*.tex` dari bagian pengesahan untuk proposal tugas akhir.
- **_Folder_ `gambar`**, berisi _file_ `*.jpg`, `*.png`, maupun format gambar lain yang akan dimasukkan pada dokumen.
- **_File_ `pustaka/pustaka.bib`**, berisi daftar referensi yang akan dimasukkan pada dokumen.

> Penjelasan lebih lanjut mengenai modifikasi pada template akan dijelaskan dengan _comment_ yang bisa dilihat langsung pada masing masing _file_ yang tersedia.

## Kontribusi

Karena keterbatasan pengetahuan mengenai aturan yang berlaku di setiap departemen di **ITS** serta agar _template_ yang dibuat ini bisa berkembang dengan fitur yang lebih banyak, diharapkan adanya kontribusi dari pihak lain yang bersedia untuk membantu.
Untuk melakukan kontribusi, siapapun bisa memulai dengan melakukan _fork_ pada repositori utama _template_ ini yang ada di [**b201lab/template-proposal-ta-its**](https://github.com/b201lab/template-proposal-ta-its), kemudian membuat perubahan dan melakukan _pull request_.
Jika terdapat masalah dari _template_ ini maupun hal yang berkaitan dengan _template_ ini, jangan ragu untuk membuat _issue_ baru pada halaman _issues_ yang bisa diakses di [sini](https://github.com/b201lab/template-proposal-ta-its/issues).