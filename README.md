# Praktikum 1: Dasar HTML

## Nama: Syafarudiansya
## NIM: 312410381
## Kelas: TI 24 A6

PENJELASAN PRAKTIKUM

1. Membuat Paragraf
   Paragraf pada HTML dibuat menggunakan tag `<p>`. Tag ini berfungsi untuk membungkus teks agar ditampilkan sebagai sebuah paragraf yang utuh, dengan jarak otomatis antar paragraf sehingga isi tulisan lebih rapi dan mudah dibaca.
   
   ```lab1_tag_dasar.html
<p align="center">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
tag-tag dasar HTML.</p>
<h2>Paragraf pada HTML</h2><!-- Ini adalah paragraf kedua -->
<p align="left">Ini merupakan sebuah paragraf yang terdiri dari beberapa
kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
dengan menggunakan tag dasar html.</p>
```
![1](Screenshots/.png)

3. Membuat Judul
   Judul pada HTML dibuat menggunakan tag heading `<h1>` sampai `<h6>`, di mana `<h1>` adalah yang paling besar dan penting. Tag ini berfungsi untuk memberi struktur hierarki pada halaman web, sehingga teks lebih terorganisir dan mudah dibaca.
4. Memformat Teks
   HTML menyediakan berbagai tag untuk memformat teks, misalnya `<b>` atau `<strong>` untuk menebalkan huruf, `<i>` atau `<em>` untuk memiringkan huruf, `<ins>` untuk garis bawah, dan '<mark>' untuk menyorot teks dengan highlight. Dengan tag-tag ini, teks pada halaman web bisa lebih jelas, menonjol, dan mudah dipahami sesuai konteks.
   
   - "Pemrograman Web" dengan tag `<b>`
   - "Teknik Informatika" dengan tag `<i>`
   - "HTML dasar" dengan tag `<mark>`
   - "Universitas Pelita Bangsa" dengan tag `<ins>`
5. Menyisipkan Gambar
   Untuk nampilin gambar di halaman web, kita pakai tag `<img>`. Tag ini tidak perlu ditutup (self-closing). Yang paling penting ada atribut src, buat nunjukin lokasi file gambarnya, sama alt, buat teks pengganti kalau gambarnya nggak kebuka. Kalau mau, bisa juga ditambahin width sama height biar ukurannya pas.
6. Membuat Hyperlink
   Hyperlink di HTML dipakai buat ngarahin pengguna ke halaman lain atau ke bagian tertentu dalam sebuah halaman. Tag yang dipakai adalah `<a>`, biasanya disertai atribut href buat menentukan alamat tujuan. Dengan hyperlink, halaman web bisa saling terhubung sehingga pengguna lebih mudah berpindah dari satu informasi ke informasi lain.


Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag?
=Tidak

2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
   
   =`<p>`: digunakan untuk membuat paragraf baru. Secara default ada jarak (margin) atas dan bawah.
    `<br>`: digunakan untuk break line (pindah ke baris baru) tanpa membuat paragraf baru. Tidak ada jarak tambahan seperti pada <p>
     
3. Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya!
   
   alt: digunakan untuk menampilkan teks alternatif ketika gambar tidak bisa ditampilkan. Juga penting untuk aksesibilitas (screen reader).
   title: memberikan keterangan tambahan berupa tooltip ketika kursor diarahkan ke gambar.
   
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

Jika hanya salah satu atribut diisi (misalnya width saja), maka browser akan otomatis menyesuaikan sisi lainnya agar gambar tetap proporsional.
Kalau keduanya diisi tapi tidak sesuai rasio asli gambar, gambar bisa terlihat stretch (terlalu lebar/tinggi).

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

 _blank: membuka link di tab/jendela baru, 

 _self: membuka link di tab/jendela yang sama (default), 

 _top: membuka link di frame paling atas (jika ada frame/iframe, akan keluar dari frame dan tampil di jendela utama), 

 _parent: membuka link di frame induk (jika ada nested frame).

PENJELASAN PRAKTIKUM

1. Membuat Paragraf
   Paragraf pada HTML dibuat menggunakan tag `<p>`. Tag ini berfungsi untuk membungkus teks agar ditampilkan sebagai sebuah paragraf yang utuh, dengan jarak otomatis antar paragraf sehingga isi tulisan lebih rapi dan mudah dibaca.
2. Membuat Judul
   Judul pada HTML dibuat menggunakan tag heading `<h1>` sampai `<h6>`, di mana `<h1>` adalah yang paling besar dan penting. Tag ini berfungsi untuk memberi struktur hierarki pada halaman web, sehingga teks lebih terorganisir dan mudah dibaca.
3. Memformat Teks
   HTML menyediakan berbagai tag untuk memformat teks, misalnya `<b>` atau `<strong>` untuk menebalkan huruf, `<i>` atau `<em>` untuk memiringkan huruf, `<ins>` untuk garis bawah, dan '<mark>' untuk menyorot teks dengan highlight. Dengan tag-tag ini, teks pada halaman web bisa lebih jelas, menonjol, dan mudah dipahami sesuai konteks.
   
   - "Pemrograman Web" dengan tag `<b>`
   - "Teknik Informatika" dengan tag `<i>`
   - "HTML dasar" dengan tag `<mark>`
   - "Universitas Pelita Bangsa" dengan tag `<ins>`
4. Menyisipkan Gambar
   Untuk nampilin gambar di halaman web, kita pakai tag `<img>`. Tag ini tidak perlu ditutup (self-closing). Yang paling penting ada atribut src, buat nunjukin lokasi file gambarnya, sama alt, buat teks pengganti kalau gambarnya nggak kebuka. Kalau mau, bisa juga ditambahin width sama height biar ukurannya pas.
5. Membuat Hyperlink
   Hyperlink di HTML dipakai buat ngarahin pengguna ke halaman lain atau ke bagian tertentu dalam sebuah halaman. Tag yang dipakai adalah `<a>`, biasanya disertai atribut href buat menentukan alamat tujuan. Dengan hyperlink, halaman web bisa saling terhubung sehingga pengguna lebih mudah berpindah dari satu informasi ke informasi lain.
