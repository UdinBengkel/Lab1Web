# Lab1Web
Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag?
=Tidak

2. Apa perbedaan dari tag "p" dengan tag "br", berikan penjelasannya!
   
   ="p": digunakan untuk membuat paragraf baru. Secara default ada jarak (margin) atas dan bawah.
    "br": digunakan untuk break line (pindah ke baris baru) tanpa membuat paragraf baru. Tidak ada jarak tambahan seperti pada <p>
     
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
   
   alt: digunakan untuk menampilkan teks alternatif ketika gambar tidak bisa ditampilkan. Juga penting untuk aksesibilitas (screen reader).
   title: memberikan keterangan tambahan berupa tooltip ketika kursor diarahkan ke gambar.
   
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
=Jika hanya salah satu atribut diisi (misalnya width saja), maka browser akan otomatis menyesuaikan sisi lainnya agar gambar tetap proporsional.
 Kalau keduanya diisi tapi tidak sesuai rasio asli gambar, gambar bisa terlihat stretch (terlalu lebar/tinggi).

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
=
 _blank: membuka link di tab/jendela baru, 
 _self: membuka link di tab/jendela yang sama (default), 
 _top: membuka link di frame paling atas (jika ada frame/iframe, akan keluar dari frame dan tampil di jendela utama), 
 _parent: membuka link di frame induk (jika ada nested frame).
